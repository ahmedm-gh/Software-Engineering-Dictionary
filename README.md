# 📖 Software Engineering & Tech Management Dictionary - Bilingual Edition

القاموس الشامل لمصطلحات هندسة البرمجيات وإدارة المشاريع التقنية (إنجليزي / عربي).

دليل مرجعي للمهندسين، المطورين، ومديري المشاريع لفهم وتوحيد لغة التخاطب التقنية في بيئات العمل.

## Table of Contents / جدول المحتويات

* [Hardware & Computing / المكونات المادية والأساسيات التحتية](#hardware--computing)
* [Programming Foundations / الهيكلية البرمجية وأسس كتابة الشيفرة](#programming-foundations)
* [Software Architecture / النماذج المعمارية للبرمجيات وتصميم النظم](#software-architecture)
* [Design Patterns & Repos / استراتيجيات إدارة المستودعات وأنماط التصميم](#design-patterns--repos)
* [Software Quality / جودة البرمجيات والديون الفنية](#software-quality)
* [Cloud & DevOps / البنية التحتية، السحابة، وأتمتة العمليات](#cloud--devops)
* [Testing & QA / ضمان جودة البرمجيات وأنماط الاختبار](#testing--qa)
* [Project Management / إدارة المشاريع والمنهجيات التقليدية](#project-management)
* [Agile Methodologies / منهجيات التطوير المرنة](#agile-methodologies)
* [Future Trends / التوجهات المستقبلية: البيانات والذكاء الاصطناعي](#future-trends)

---

<div align="center">

**المكونات المادية والأساسيات التحتية**

## Hardware & Computing

</div>

### Hardware / العتاد الصلب / المكونات المادية

**Definition:**

* The physical entity of computers, servers, and networking equipment.
* Represents the physical foundation on which all software operations and architectural abstractions are built and executed.

**التعريف:**

* الكيان المادي لأجهزة الحاسوب والخوادم ومعدات الشبكات.
* يمثل الأساس الفيزيائي الذي تُبنى وتُنفذ عليه كافة العمليات البرمجية والتجريدات المعمارية.

---

### CPU - Central Processing Unit / وحدة المعالجة المركزية

**Definition:**

* Commonly referred to as "the processor."
* The operational brain of the computer, responsible for executing micro instructions through complex arithmetic and logical operations that power all systems.

**التعريف:**

* يُعرف اصطلاحاً بـ "المعالج".
* هو الدماغ المشغل للحاسوب، حيث يتولى تنفيذ التعليمات البرمجية الدقيقة عبر إجراء العمليات الحسابية والمنطقية المعقدة لتشغيل الأنظمة.

---

### RAM - Random Access Memory / ذاكرة الوصول العشوائي

**Definition:**

* The primary temporary memory the system relies on to store data and running applications.
* Provides ultra-fast access for the processor compared to permanent storage.

**التعريف:**

* الذاكرة الرئيسية المؤقتة التي يعتمد عليها النظام لتخزين البيانات والتطبيقات أثناء تشغيلها الفعلي.
* توفر وصولاً فائق السرعة للمعالج مقارنة بالتخزين الدائم.

---

### Hard Disk / Drive / القرص الصلب / محرك الأقراص

**Definition:**

* The permanent storage medium for data, files, operating systems, and databases.
* Its importance lies in preserving system state and storing information indefinitely.

**التعريف:**

* وسيط التخزين الدائم للبيانات، والملفات، ونظم التشغيل، وقواعد البيانات.
* تكمن أهميته في الحفاظ على حالة النظام (State) وتخزين المعلومات لفترات غير محدودة.

---

### Motherboard / اللوحة الأم

**Definition:**

* The central electronic base that connects and coordinates communication between all hardware components (processor, memory, expansion cards).
* Serves as the physical data transport bridge.

**التعريف:**

* القاعدة الإلكترونية المركزية التي تربط وتنسق التواصل بين جميع المكونات المادية (المعالج، الذاكرة، وبطاقات التوسعة).
* تمثل الجسر الناقل للبيانات المادية.

---

### Bandwidth / عرض الحزمة / النطاق الترددي

**Definition:**

* The maximum data transfer capacity through a network path or communication channel in a given time period.
* A critical metric for determining the quality and efficiency of internet-dependent applications.

**التعريف:**

* سعة نقل البيانات القصوى عبر مسار شبكي أو قناة اتصال في فترة زمنية محددة.
* يُعتبر مقياساً حاسماً لتحديد جودة وكفاءة التطبيقات التي تعتمد على الإنترنت.

---

### Cache / الذاكرة المخبأة / المخبأ

**Definition:**

* Ultra-fast storage space where frequently or soon-to-be-needed data is kept.
* Reduces latency and decreases the load on core database resources.

**التعريف:**

* مساحة تخزين فائقة السرعة تُحفظ فيها البيانات التي يُتوقع الحاجة إليها قريباً أو بشكل متكرر.
* تقلل زمن الاستجابة (Latency) وتقلل العبء على الموارد الأساسية لقواعد البيانات.

> [!TIP]
> Cache is one of the most impactful performance optimizations. "There are only two hard problems in CS: cache invalidation and naming things."
>
> الكاش من أقوى أدوات تحسين الأداء. من أشهر اقتباسات البرمجة: "في علوم الحاسوب مشكلتان صعبتان فقط: إبطال الكاش وتسمية الأشياء."

---

### Buffer / حاجز تخزين مؤقت / التخزين الوسيط

**Definition:**

* A physical memory area used to temporarily absorb and store data as it moves between devices or processes running at different speeds.
* Ensures continuous data flow without loss.

**التعريف:**

* منطقة ذاكرة مادية تُستخدم لاستيعاب البيانات وتخزينها بصورة مؤقتة أثناء انتقالها بين أجهزة أو عمليات تعمل بسرعات مختلفة.
* تضمن تدفقاً متصلاً للبيانات دون فقدان.

---

### Digital vs. Analog / رقمي مقابل تناظري

**Definition:**

* **Digital**: Represents data as a series of zeros and ones (Bits).
* **Analog**: Relies on continuously variable signals.
* All modern computing is built entirely on digital systems.

**التعريف:**

* **رقمي**: يعتمد على تمثيل البيانات كسلسلة من الأصفار والآحاد (Bits).
* **تناظري**: يعتمد على إشارات متصلة متغيرة.
* الحوسبة الحديثة تُبنى كلياً على الأنظمة الرقمية.

---

### Byte / بايت

**Definition:**

* The fundamental unit of measurement for computer storage capacity.
* One byte consists of 8 bits. Larger measurements scale from it: Kilobyte, Megabyte, Gigabyte, etc.

**التعريف:**

* وحدة القياس الأساسية لسعة التخزين في الحواسيب.
* يتكون البايت الواحد من 8 بتات (Bits). تتدرج منه القياسات الأكبر كالكيلوبايت والميجابايت والجيجابايت.

---

<div align="center">
  
**الهيكلية البرمجية وأسس كتابة الشيفرة**

## Programming Foundations

</div>

### Source Code / الشيفرة المصدرية / الكود المصدري

**Definition:**

* A collection of instructions written in human-readable text form by a programmer using a programming language.
* Represents the logical rules that make up any application or website.

**التعريف:**

* مجموعة التعليمات المكتوبة بصيغة نصية قابلة للقراءة البشرية بواسطة مبرمج باستخدام إحدى لغات البرمجة.
* تمثل القواعد المنطقية التي يتكون منها أي تطبيق أو موقع إلكتروني.

---

### Syntax / بناء الجملة / القواعد النحوية

**Definition:**

* The strict linguistic and structural rules dictating how symbols and keywords must be written in a given programming language.
* Must be correct and understandable to the Compiler.

**التعريف:**

* القواعد اللغوية والهيكلية الصارمة التي تُملي كيفية كتابة الرموز والكلمات المفتاحية في لغة برمجة معينة.
* يجب أن تكون صحيحة ومفهومة بالنسبة للمترجم (Compiler).

> [!NOTE]
> A single syntax error can prevent an entire program from compiling. Modern IDEs highlight syntax errors in real-time.
>
> خطأ نحوي واحد يمكن أن يمنع البرنامج كله من الترجمة. بيئات التطوير الحديثة تُبرز هذه الأخطاء فورياً.

---

### Structure / الهيكلية / البنية التنظيمية

**Definition:**

* The way code, data, or files are organized within a project to ensure readability and scalability.
* Unstructured code leads to what is known as "Spaghetti Code."

**التعريف:**

* الطريقة التي يتم بها ترتيب الكود البرمجي، البيانات، أو الملفات داخل المشروع لضمان قابليتها للقراءة والتوسع.
* الكود عديم الهيكلية يؤدي لاحقاً إلى ما يُعرف بـ "شيفرة السباغيتي" (Spaghetti Code).

---

### Low-level / منخفض المستوى

**Definition:**

* Refers to programming languages or operations very close to machine language, lacking abstraction layers.
* Grants the programmer direct and complete control over physical system resources (RAM, processor).
* Used in developing operating systems and embedded software.

**التعريف:**

* يُشير إلى لغات البرمجة أو العمليات شديدة القرب من لغة الآلة، وتفتقر إلى طبقات التجريد.
* تمنح المبرمج تحكماً مباشراً وكاملاً بموارد النظام المادية (كالرام والمعالج).
* تُستخدم في تطوير أنظمة التشغيل والبرامج المدمجة.

---

### High-level / عالي المستوى

**Definition:**

* Programming languages that provide a high degree of abstraction and move away from machine language complexities.
* Used to accelerate development and focus on Business Logic rather than managing physical system resources.

**التعريف:**

* لغات برمجة توفر درجة عالية من التجريد وتبتعد عن تعقيدات لغة الآلة.
* تُستخدم لتسريع عملية التطوير والتركيز على المنطق التجاري (Business Logic) بدلاً من إدارة موارد النظام المادية.

---

### Algorithm / خوارزمية

**Definition:**

* A finite and clearly defined series of mathematical or logical instructions designed to solve a problem or accomplish a task.
* The core of all computing operations and data processing.

**التعريف:**

* سلسلة متناهية ومحددة بوضوح من التعليمات الرياضية أو المنطقية المُصممة لحل مشكلة أو إنجاز مهمة.
* هي جوهر عمليات الحوسبة ومعالجة البيانات.

---

### Compiler / المترجم البرمجي

**Definition:**

* A complex program whose job is to read source code written in a high-level language.
* Translates it all at once into low-level executable code (machine language) for the processor to understand and execute.

**التعريف:**

* برنامج معقد وظيفته قراءة الشيفرة المصدرية المكتوبة بلغة عالية المستوى.
* يترجمها دفعة واحدة إلى شيفرة تنفيذية منخفضة المستوى (لغة الآلة) لكي يفهمها وينفذها المعالج.

---

### Variable / متغيّر

**Definition:**

* A symbolic storage space reserved in computer memory during execution.
* Carries a specific name and holds data that can be modified throughout the program's runtime lifecycle.

**التعريف:**

* مساحة تخزينية رمزية يتم حجزها في ذاكرة الحاسوب أثناء التنفيذ.
* تحمل اسماً معيناً وتُستخدم للاحتفاظ ببيانات قابلة للتعديل والتغيير خلال دورة حياة تشغيل البرنامج.

---

### Integer / عدد صحيح

**Definition:**

* A basic data type representing any whole positive or negative number, or zero.
* Does not accept fractions or decimal parts in its programming calculations.

**التعريف:**

* نوع من أنواع البيانات الأساسية (Data Types) يُمثل أي رقم كامل موجب أو سالب أو الصفر.
* لا يقبل الكسور أو الأجزاء العشرية في حساباته البرمجية.

---

### Boolean / نوع البيانات المنطقية

**Definition:**

* A simple data type holding only one of two values: `True` or `False`.
* The cornerstone of all conditional operations and decision-making (`If/Else`) inside code.

**التعريف:**

* نوع بيانات بسيط يحمل واحدة من قيمتين فقط: صواب (`True`) أو خطأ (`False`).
* يُعد حجر الأساس لكافة العمليات الشرطية واتخاذ القرارات (`If/Else`) داخل الكود.

---

### Loop / حلقة تكرارية

**Definition:**

* A programming control structure that directs the processor to repeatedly execute a specific block of instructions until a condition is met.
* Essential for handling large data lists without rewriting code.

**التعريف:**

* هيكل تحكم برمجي يوجه المعالج لإعادة تنفيذ كتلة محددة من التعليمات بشكل مستمر حتى يتم استيفاء شرط معين.
* ضروري للتعامل مع قوائم البيانات الكبيرة دون تكرار كتابة الكود.

---

### Function / دالّة / وظيفة

**Definition:**

* A group of programming lines encapsulated together that perform one specific task.
* Can be called from anywhere in the project, reinforcing the DRY (Don't Repeat Yourself) principle.

**التعريف:**

* مجموعة من الأسطر البرمجية المغلفة معاً والتي تقوم بتنفيذ مهمة واحدة ومحددة.
* يمكن استدعاؤها في أي مكان في المشروع، مما يعزز مبدأ عدم تكرار الكود (DRY).

> [!IMPORTANT]
> A function should do ONE thing and do it well. Functions with multiple responsibilities are a sign of poor design and a common source of bugs.
>
> الدالة الجيدة تؤدي مهمة واحدة فقط وتؤديها بإتقان. الدوال متعددة المهام علامة على تصميم ضعيف ومصدر شائع للأخطاء.

---

### Nested / متداخل / متضمن

**Definition:**

* A concept referring to placing a programming structure inside another of the same type.
* Such as placing a function inside a function, or a loop inside another loop, to build complex multi-dimensional logic.

**التعريف:**

* مفهوم يُشير إلى وضع هيكل برمجي داخل هيكل آخر من نفس النوع.
* كوضع دالة داخل دالة، أو حلقة تكرارية داخل حلقة تكرارية أخرى، لبناء منطق مركب ومتعدد الأبعاد.

---

### Object / كائن

**Definition:**

* The core component in Object-Oriented Programming (OOP).
* Represents a complete programming package containing properties (data) and methods (functions) reflecting a real-world entity.

**التعريف:**

* المكون الأساسي في "البرمجة الموجهة للكائنات" (OOP).
* يمثل حزمة برمجية متكاملة تحتوي على خصائص (بيانات) وطرق (دوال) تعكس كياناً حقيقياً، ويمكن الإشارة إليه ومعالجته كوحدة واحدة.

---

### Array / مصفوفة

**Definition:**

* A linear data structure used to store a collection of sequential values or variables of the same type.
* Any element can be accessed via its own Index.

**التعريف:**

* هيكل بيانات خطي يُستخدم لتخزين مجموعة من القيم أو المتغيرات المتسلسلة من نفس النوع.
* يُمكن الوصول إلى أي عنصر فيها عبر الفهرس (Index) الخاص به.

---

### Hash Table / جدول التقطيع / جدول التجزئة

**Definition:**

* An advanced data structure that implements an associative array.
* Maps Keys to Values using a Hash Function, providing ultra-fast search and insertion operations.

**التعريف:**

* بنية بيانات متقدمة تُنفذ مصفوفة ترابطية.
* تقوم بتعيين مفاتيح (Keys) إلى قيم (Values) باستخدام دالة تجزئة (Hash Function)، مما يتيح سرعة فائقة في عمليات البحث والإضافة.

---

### Terminal / Console / الواجهة الطرفية / سطر الأوامر

**Definition:**

* A text-based interface allowing developers to interact directly with the operating system by entering text commands without relying on a graphical interface.
* A vital tool in server management and deployment operations.

**التعريف:**

* واجهة تعتمد كلياً على النصوص، تسمح للمطورين بالتفاعل مباشرة مع نظام التشغيل عن طريق إدخال أوامر نصية دون الاعتماد على واجهة رسومية.
* وهو أداة حيوية في إدارة الخوادم وعمليات النشر.

---

### Bug / خطأ برمجي / خلل

**Definition:**

* A defect, shortcoming, or logical/structural error in the source code.
* Leads to incorrect results, unexpected behavior, or a complete application crash.

**التعريف:**

* عيب، قصور، أو خطأ منطقي أو هيكلي في الشيفرة المصدرية.
* يؤدي إلى نتائج غير صحيحة، أو سلوك غير متوقع، أو توقف التطبيق بالكامل عن العمل.

> [!NOTE]
> The term "Bug" was popularized in 1947 when Grace Hopper found an actual moth stuck inside a computer relay, causing a malfunction.
>
> مصطلح "Bug" اشتُهر عام 1947 حين وجدت Grace Hopper عثّةً (حشرة ليلية) حقيقية عالقة في دائرة كمبيوتر كانت تسبب خللاً في التشغيل.

---

<div align="center">
  
**النماذج المعمارية للبرمجيات وتصميم النظم**

## Software Architecture

</div>

### Architecture / البنية المعمارية

**Definition:**

* The comprehensive structural framework for system design.
* Includes defining software components, the interfaces through which they communicate, and their behavior - achieving both functional and non-functional requirements such as security and scalability.

**التعريف:**

* الإطار الهيكلي الشامل لتصميم النظام.
* يشمل تحديد مكونات البرمجيات، الواجهات التي تتواصل من خلالها، وسلوكها، بما يحقق متطلبات المشروع الوظيفية وغير الوظيفية كالأمان والتوسع.

---

### Core System / النظام الأساسي / جوهر النظام

**Definition:**

* The central programming block containing the most critical Business Rules of a project.
* The pivot point that all other peripheral components depend on to function.

**التعريف:**

* الكتلة البرمجية المركزية التي تحتوي على قواعد الأعمال (Business Rules) الأكثر أهمية في المشروع.
* تعتبر نقطة الارتكاز التي تعتمد عليها باقي المكونات الجانبية للعمل.

---

### Middleware / البرمجيات الوسيطة

**Definition:**

* Software acting as a translation and linking layer behind the scenes between the OS and distributed applications across the network.
* Or between the backend and databases, ensuring smooth data transfer and tracking.

**التعريف:**

* برامج تعمل كطبقة ترجمة وربط وسيطة خلف الكواليس بين نظام التشغيل والتطبيقات الموزعة عبر الشبكة.
* أو بين الواجهة الخلفية وقواعد البيانات. تضمن نقل البيانات بانسيابية وتتبع الحركات.

---

### Backend / الجهة الخلفية

**Definition:**

* The hidden part of a software project's structure.
* Usually includes the main Server, the processing application, and the Database. Responsible for computational processing and storage.

**التعريف:**

* الجزء الخفي من بنية المشروع البرمجي.
* يشمل عادةً الخادم الأساسي (Server)، التطبيق المعالج، وقاعدة البيانات (Database). يتكفل بإجراء المعالجات الحسابية والتخزين.

---

### Frontend / الجهة الأمامية

**Definition:**

* The graphical and interactive interface that the end user sees and interacts with (whether a website or a mobile app).
* Fed with data by the "Backend."

**التعريف:**

* الواجهة الرسومية والتفاعلية التي يراها المستخدم النهائي ويتفاعل معها (سواء كانت موقع ويب أو تطبيق هاتف).
* يتم تغذيتها بالبيانات من قِبل "الجهة الخلفية".

---

### Dependency / الاعتمادية / التبعية

**Definition:**

* Refers to the state where a software module or Package depends on another to function correctly.
* Managing these dependencies is one of the most complex tasks in maintaining large projects to prevent version conflicts.

**التعريف:**

* تشير إلى حالة ارتباط وحدة برمجية أو حزمة (Package) بوحدة أخرى لتتمكن من العمل بصورة صحيحة.
* إدارة هذه الاعتماديات تعتبر من أعقد مهام صيانة المشاريع الكبيرة لمنع تضارب الإصدارات.

---

### Abstractions / التجريد / المستخلصات

**Definition:**

* An architectural principle aiming to hide the internal complexities of a system from the user or developer.
* Only the simple interface is exposed for interaction without needing to know the internal working mechanisms.

**التعريف:**

* مبدأ معماري يهدف إلى إخفاء تعقيدات النظام الداخلية عن المستخدم أو عن المطور.
* بحيث يُعرض فقط الواجهة البسيطة للتفاعل دون الحاجة لمعرفة آليات العمل الداخلية المعقدة.

---

### Implementation / التنفيذ / التطبيق الفعلي

**Definition:**

* The process of translating concepts, designs, and algorithms (or abstract interfaces) into written, effective source code capable of processing data within the system.

**التعريف:**

* عملية ترجمة المفاهيم، التصميمات، والخوارزميات (أو الواجهات التجريدية).
* وتحويلها إلى شيفرة مصدرية مكتوبة وفعالة وقادرة على معالجة البيانات داخل النظام.

---

### Utils - Utilities / أدوات مساعدة / وحدات خدمية

**Definition:**

* Folders or Modules containing small, independent functions reusable throughout the project.
* Perform routine tasks (like simple encryption or text manipulation) without being tied to Business Logic.

**التعريف:**

* مجلدات أو وحدات برمجية (Modules) تحتوي على دوال ووظائف صغيرة مستقلة يمكن إعادة استخدامها في جميع أنحاء المشروع.
* لإجراء مهام روتينية (مثل التشفير البسيط، أو التلاعب بالنصوص) دون الارتباط بالمنطق التجاري.

---

### Modular Programming / البرمجة التركيبية / المعيارية

**Definition:**

* A design methodology that relies on dividing a program into small, independent Modules.
* Each performs a specific function, making them easier to test, modify, and reuse in other projects.

**التعريف:**

* منهجية تصميم تعتمد على تقسيم البرنامج إلى أجزاء ووحدات (Modules) صغيرة ومستقلة.
* كل منها يؤدي وظيفة محددة، مما يسهل اختبارها، تعديلها، وإعادة استخدامها في مشاريع أخرى.

---

### API - Application Programming Interface / واجهة برمجة التطبيقات

**Definition:**

* A set of protocols and tools that allow different applications and systems to communicate and exchange data programmatically and securely in a unified manner.

**التعريف:**

* مجموعة البروتوكولات والأدوات التي تتيح للتطبيقات والأنظمة المختلفة التحدث وتبادل البيانات مع بعضها البعض برمجياً.
* وبشكل آمن وموحد.

> [!IMPORTANT]
> A well-designed API is like a good contract - clear, stable, and doesn't surprise the caller. Bad APIs are the #1 source of integration headaches.
>
> الـ API المصمم بشكل جيد يشبه العقد الواضح - ثابت ولا يُفاجئ المستخدم. الـ APIs السيئة هي المصدر الأول لصداع التكاملات.

---

<div align="center">
  
**استراتيجيات إدارة المستودعات وأنماط التصميم**

## Design Patterns & Repos

</div>

### Monorepo / المستودع الأحادي / الموحد

**Definition:**

* An architectural pattern and version control strategy relying on storing source code for multiple interrelated projects in a single centralized repository.
* Greatly facilitates code sharing and broad updates, but requires powerful build tools like Turborepo to avoid slowdowns.

**التعريف:**

* نمط معماري واستراتيجية لإدارة النسخ (Version Control) يعتمد على تخزين الشيفرة المصدرية لمشاريع وتطبيقات وحزم متعددة داخل مستودع بيانات مركزي واحد.
* يسهل جداً عمليات مشاركة الكود والتحديثات الشاملة، ولكنه يتطلب أدوات بناء قوية كـ Turborepo لتفادي بطء العمل مع زيادة حجمه.

---

### Polyrepo / Multi-repo / المستودعات المتعددة

**Definition:**

* A strategy relying on creating an independent code repository for each project or service separately.
* Grants complete independence to development teams and freedom in technology choices, but creates challenges in dependency synchronization and sharing Utils between different projects.

**التعريف:**

* استراتيجية تعتمد على إنشاء مستودع كود مستقل لكل مشروع أو خدمة (Service) على حدة.
* يمنح استقلالية كاملة لفرق التطوير وحرية في اختيار التقنيات، لكنه يخلق تحديات في تزامن الاعتماديات وصعوبة مشاركة الشيفرات المساعدة (Utils) بين المشاريع المختلفة.

---

### Microservices / الخدمات المصغرة

**Definition:**

* An architectural approach where the application is built as a collection of small, independent services.
* Each service runs in its own process and communicates via lightweight mechanisms (usually APIs).
* Enhances the ability to independently scale each part of the application.

**التعريف:**

* هندسة معمارية يتم فيها بناء التطبيق كمجموعة من الخدمات الصغيرة المستقلة.
* كل خدمة تعمل في عمليتها الخاصة وتتواصل بآليات خفيفة (غالباً عبر واجهات API).
* هذا النمط يعزز القدرة على التوسع المستقل لكل جزء من التطبيق.

---

### MVC - Model-View-Controller / نمط النموذج والعرض ووحدة التحكم

**Definition:**

* **`Model`**: Handles data and Business Logic.
* **`View`**: The graphical user interface.
* **`Controller`**: An intermediary that interprets user inputs and updates both the Model and View.
* May cause bottlenecks in very complex interfaces.

**التعريف:**

* **`النموذج`**: يعالج البيانات والمنطق التجاري.
* **`العرض`**: واجهة المستخدم الرسومية.
* **`وحدة التحكم`**: وسيط يفسر مدخلات المستخدم ويحدث النموذج والعرض.
* قد يسبب اختناقات في الواجهات المعقدة جداً.

---

### MVP - Model-View-Presenter / نمط النموذج والعرض والمُقَدِّم

**Definition:**

* An evolution of the MVC pattern where the "Presenter" becomes the actual driver of interactions between the interface and data.
* The "View" becomes completely passive.
* Greatly benefits Unit Testing in complete isolation.

**التعريف:**

* تطور لنمط MVC حيث يصبح "المُقدِّم" (Presenter) هو المحرك الفعلي للتفاعلات بين الواجهة والبيانات.
* بينما يصبح "العرض" سلبياً تماماً.
* يفيد هذا النمط بشكل كبير في إمكانية اختبار الوحدات (Unit Testing) بشكل معزول بالكامل.

---

### MVVM - Model-View-ViewModel / نمط النموذج والعرض ونموذج العرض

**Definition:**

* A design pattern that relies heavily on automatic Data Binding between the model and the interface.
* Removes the need to write long, repetitive code to update the user interface when data changes in the backend.

**التعريف:**

* نمط تصميم يعتمد بكثافة على الربط التلقائي للبيانات (Data Binding) بين النموذج والواجهة.
* مما يزيل الحاجة لكتابة أكواد طويلة ومكررة لتحديث واجهة المستخدم عند تغير البيانات في الخلفية.

---

### Singleton Pattern / نمط النسخة المفردة

**Definition:**

* One of the Creational Patterns. Restricts instantiation of a Class to a single object only.
* Provides a global access point to it.
* Useful in controlling shared resources like database connections.

**التعريف:**

* أحد أنماط إنشاء الكائنات (Creational Patterns). يقيد إنشاء فئة (Class) بنسخة كائن واحدة فقط.
* يوفر نقطة وصول عالمية (Global) إليها.
* مفيد في التحكم بالموارد المشتركة مثل اتصالات قواعد البيانات.

---

### Factory Pattern / نمط المصنع

**Definition:**

* A Creational Pattern that isolates the process of Object Creation in a dedicated function or class.
* Allows subclasses to determine and change objects to be created without touching the original calling code.

**التعريف:**

* نمط إنشائي يعزل عملية إنشاء الكائنات (Object Creation) في دالة أو فئة مخصصة.
* مما يسمح للفئات الفرعية بتحديد الكائنات المراد إنشاؤها وتغييرها دون المساس بالشيفرة الأصلية المستدعية للوظيفة.

---

<div align="center">
  
**جودة البرمجيات والديون الفنية**

## Software Quality

</div>

### Boilerplate Code / الكود المعياري / القوالب البرمجية

**Definition:**

* Sections and blocks of source code that are reused and copied across different contexts and projects with little or no modification.
* Saves time in project setup (Scaffolding), but overuse increases complexity and overall maintenance difficulty.

**التعريف:**

* أجزاء وكتل نصية من الشيفرة المصدرية يتم إعادة استخدامها ونسخها في سياقات ومشاريع مختلفة مع إجراء تعديلات طفيفة أو معدومة.
* يوفر الوقت في إعداد المشاريع (Scaffolding)، ولكن الإفراط في استخدامه يزيد من التعقيد وصعوبة الصيانة الشاملة.

---

### Legacy Code / الشيفرة القديمة / الموروثة

**Definition:**

* Code written long ago that still runs within the system, but modifying it has become extremely dangerous and difficult.
* Due to lack of documentation, absence of original programmers, or absence of test coverage.
* The primary cause of bottlenecks in old banking and government systems.

**التعريف:**

* شيفرة برمجية مكتوبة قديماً وتعمل بداخل النظام، لكن التعديل عليها أصبح بالغ الخطورة والصعوبة.
* لغياب التوثيق، غياب المبرمجين الأصليين، أو عدم وجود اختبارات برمجية تغطيها.
* هي المسبب الأول للاختناقات في الأنظمة البنكية والحكومية القديمة.

> [!CAUTION]
> Never modify Legacy Code without first writing tests to cover its current behavior. "If it ain't broke, don't fix it" - but wrap it in tests before you even look at it.
>
> لا تعدّل على الـ Legacy Code أبداً قبل كتابة اختبارات تغطي سلوكه الحالي. "إذا كان يعمل فلا تلمسه" - لكن اكتب له اختبارات قبل أن تقترب منه.

---

### Technical Debt / الدين الفني / التقني

**Definition:**

* The cost of additional effort and time required to refactor the program in the future.
* Result of choosing quick and easy programming methods instead of the proper engineering approach.
* Classified into: **deliberate and prudent** debt, and **inadvertent and reckless** debt.

**التعريف:**

* تكلفة الجهد والوقت الإضافي المطلوب لإعادة صياغة البرنامج مستقبلاً نتيجة اختيار أساليب برمجية سريعة وسهلة بدلاً من النهج الهندسي السليم والأطول.
* يصنف إلى ديون **متعمدة وحكيمة**، وأخرى **غير متعمدة ومتهورة**.

---

### Architecture Debt / دين البنية المعمارية

**Definition:**

* A dangerous type of Technical Debt arising from poor structural choices in project foundations.
* Hinders system scalability and requires demolishing large parts of it to fix.

**التعريف:**

* نوع خطير من الديون الفنية ينشأ عن اختيارات هيكلية سيئة في أساسات المشروع.
* مما يُعيق توسع النظام لاحقاً ويستلزم هدم أجزاء واسعة منه لإصلاحه.

---

### Documentation Debt / دين التوثيق

**Definition:**

* The absence, shortage, or obsolescence of documents and explanations accompanying the project's source code.
* Obstructs onboarding of new developers and reduces technical support team efficiency.

**التعريف:**

* غياب أو نقص أو تقادم المستندات والشروحات التي ترافق الشيفرة المصدرية للمشروع.
* مما يعرقل عملية تأهيل المبرمجين الجدد ويقلل كفاءة فريق الدعم الفني.

---

### Refactoring / إعادة الهيكلة / إعادة التصميم

**Definition:**

* A deliberate engineering process aimed at changing the internal structure of source code to make it clearer, more organized, and less complex.
* **Key condition**: This change must not cause any modification to the program's visible functions and behavior.

**التعريف:**

* عملية هندسية مدروسة تهدف إلى تغيير بنية الكود المصدري من الداخل لجعله أكثر وضوحاً، تنظيماً، وأقل تعقيداً.
* **بشرط** ألا يؤدي هذا التغيير إلى إحداث أي تعديل في وظائف البرنامج وسلوكه الظاهر للمستخدم.

---

### Code Duplication / تكرار الشيفرة / التكرار البرمجي

**Definition:**

* The presence of identical or very similar programming texts in more than one place within the system.
* Leads to multiplying system Bugs and requiring updates to several scattered files upon any change.

**التعريف:**

* وجود نصوص برمجية متطابقة أو متشابهة جداً في أكثر من مكان داخل النظام.
* يؤدي ذلك إلى مضاعفة أخطاء النظام (Bugs) والحاجة لتحديث عدة ملفات متفرقة عند أي تغيير.

---

<div align="center">
  
**البنية التحتية، السحابة، وأتمتة العمليات**

## Cloud & DevOps

</div>

### Infrastructure / البنية التحتية

**Definition:**

* All physical and software components, networks, routers, computing resources, and core databases necessary to host and run applications and IT services.
* Makes them available to the end user.

**التعريف:**

* كافة المكونات المادية والبرمجية، الشبكات، أجهزة التوجيه، موارد الحوسبة، وقواعد البيانات الأساسية اللازمة لاستضافة وتشغيل التطبيقات وخدمات تكنولوجيا المعلومات.
* وإتاحتها للمستخدم النهائي.

---

### Cloud Computing / الحوسبة السحابية

**Definition:**

* Technology enabling delivery of all computing resources (servers, storage, software, and analytics) on demand via the Internet.
* Instead of buying and storing them locally, thus reducing operational costs.

**التعريف:**

* تقنية تتيح تقديم كافة موارد وتقنيات النظم الحاسوبية (الخوادم، التخزين، البرمجيات، والتحليلات) عند الطلب عبر الإنترنت.
* عوضاً عن شرائها وتخزينها محلياً في مقرات الأعمال، مما يخفض التكاليف التشغيلية.

---

### DevOps / عمليات التطوير والتشغيل

**Definition:**

* An organizational culture and integrated engineering approach aiming to break the silos between Development (Dev) and Infrastructure/Operations (Ops) teams.
* Relies heavily on automation to accelerate software delivery and reduce update failure rates.

**التعريف:**

* ثقافة تنظيمية ونهج هندسي متكامل يهدف إلى كسر الصوامع بين فرق البرمجة (Dev) وفرق البنية التحتية والتشغيل (Ops).
* يعتمد بشكل كثيف على الأتمتة لتسريع وتيرة تسليم البرمجيات وتخفيف نسبة إخفاق التحديثات.

---

### Automation / الأتمتة / التشغيل الآلي

**Definition:**

* Employing pre-written technology and software to execute repetitive procedures (deployment, code testing, reporting) with complete independence and no direct human intervention.
* The main nerve of DevOps practices.

**التعريف:**

* توظيف التكنولوجيا والبرمجيات المكتوبة مسبقاً لتنفيذ إجراءات متكررة (كعمليات النشر واختبار الكود والتقارير) باستقلالية تامة وبدون أي تدخل بشري مباشر.
* وهو العصب الرئيسي لممارسات الـ DevOps.

---

### IaC - Infrastructure as Code / البنية التحتية ككود

**Definition:**

* The practice of managing systems and setting up servers and cloud networks through pre-defined programming files (like Terraform).
* Transforms server setup from a complex, slow manual task into a fast, reliable, and secure programming process.

**التعريف:**

* ممارسة إدارة النظم وإعداد الخوادم والشبكات السحابية من خلال كتابة نصوص وملفات برمجية محددة مسبقاً (مثل Terraform).
* تحول هذه العملية إعداد الخوادم من مهمة يدوية معقدة بطيئة إلى عملية برمجية سريعة وموثوقة وآمنة.

---

### CI/CD Pipeline / مسار التكامل والتسليم المستمر

**Definition:**

* **CI - Continuous Integration**: Developers' code is periodically merged and immediately tested.
* **CD - Continuous Delivery/Deployment**: Successfully tested code is automatically moved to Production environments to become available to customers.
* Accelerates the update cycle and reduces errors.

**التعريف:**

* **CI - التكامل المستمر**: يتم دمج كود المطورين دورياً واختباره فورياً.
* **CD - التسليم/النشر المستمر**: يتم نقل الكود الناجح تلقائياً إلى بيئات الإنتاج (Production) ليصبح متاحاً للعملاء.
* مما يسرع دورة التحديث ويقلل الأخطاء.

> [!IMPORTANT]
> A healthy CI/CD pipeline is the difference between releasing features in days vs. months. It's non-negotiable for any serious engineering team.
>
> مسار CI/CD السليم هو الفرق بين إصدار الميزات في أيام أو في أشهر. لا تفاوض عليه في أي فريق هندسي جاد.

---

### Containerization / Containers / تعليب البرمجيات / الحاويات

**Definition:**

* A technology for packaging an application along with all its executable files, libraries, and dependencies inside a unified, small virtual environment called a Container.
* Guarantees that code running on a developer's machine will run with perfect precision on cloud servers.

**التعريف:**

* تقنية لتغليف التطبيق مع جميع ملفاته التنفيذية ومكتباته واعتمادياته داخل بيئة افتراضية موحدة وصغيرة الحجم تسمى (حاوية).
* تضمن هذه التقنية أن الكود الذي يعمل في جهاز المطور سيعمل بدقة تامة في الخوادم السحابية.

---

### Cloud Bridge / الجسر السحابي

**Definition:**

* A secured network connection and virtual tunnel (VPN Tunnel) linking two different cloud environments, or between a cloud and local infrastructure.
* Ensures seamless direct connection and protected data exchange between distributed environments.

**التعريف:**

* اتصال شبكي ونفق افتراضي (VPN Tunnel) مؤمن يربط بين بيئتين سحابيتين مختلفتين، أو بين سحابة وبنية تحتية محلية.
* لضمان اتصال سلس ومباشر وتبادل بيانات محمي بين البيئات الموزعة.

---

<div align="center">
  
**ضمان جودة البرمجيات وأنماط الاختبار**

## Testing & QA

</div>

### Unit Testing / اختبار الوحدة

**Definition:**

* A precise and separate testing process applied to the smallest logical block in the program (such as a function or class).
* Aims to ensure this unit performs required outputs with complete accuracy.
* The fastest type of testing and reduces the cost of fixing early-discovered bugs.

**التعريف:**

* عملية اختبار دقيقة ومنفصلة تُطبق على أصغر كتلة منطقية في البرنامج (مثل دالّة أو فئة).
* يهدف إلى التأكد من أن هذه الوحدة تؤدي المخرجات المطلوبة بدقة تامة.
* هو أسرع الاختبارات ويوفر كلفة إصلاح الأخطاء المكتشفة مبكراً.

---

### Integration Testing / اختبار التكامل

**Definition:**

* A level of testing concerned with discovering interface errors and Interactions between different units and software libraries after they are assembled.
* Verifies the compatibility of their communication and data exchange.

**التعريف:**

* مستوى من مستويات الاختبار المعنية باكتشاف أخطاء واجهات الربط والتفاعلات (Interaction) بين الوحدات والمكتبات البرمجية المختلفة بعد تجميعها.
* والتأكد من توافقية اتصالها وتبادلها للبيانات.

---

### System Testing / اختبار النظام

**Definition:**

* Testing the complete and holistic software system from beginning to end.
* Ensures that all architectural components, middleware, and backend interact and work together seamlessly according to pre-defined overall specifications and requirements.

**التعريف:**

* اختبار النظام البرمجي بشكل كامل وكلّي من البداية للنهاية.
* للتأكد من أن جميع المكونات المعمارية والبرمجيات الوسيطة والخلفية تتفاعل وتعمل معاً بانسيابية وفقاً للمواصفات والمتطلبات الكلية المحددة سلفاً.

---

### UAT - User Acceptance Testing / اختبار قبول المستخدم

**Definition:**

* The final stage in the chain of evaluative tests.
* Conducted by actual customers or representatives of the end user.
* Verifies the system serves business requirements and is ready for real-world operation before handover.

**التعريف:**

* المرحلة الأخيرة والنهائية من سلسلة الاختبارات التقييمية.
* تتم من قِبل عملاء أو ممثلين حقيقيين للمستخدم النهائي للتأكد من أن النظام المطور يخدم متطلبات الأعمال.
* وقابل للتشغيل الواقعي قبل تسليمه.

---

### TDD - Test-Driven Development / التطوير القائم على الاختبار

**Definition:**

* A strict programming methodology requiring developers to write automated tests for any feature **before** writing the core code for that feature.
* This approach refines understanding of program requirements and reduces the likelihood of future defects (Defect Debt).

**التعريف:**

* منهجية برمجية صارمة تتطلب قيام المطورين بكتابة الاختبارات المؤتمتة الخاصة بأي ميزة **قبل** كتابة الشيفرة الأساسية لتلك الميزة.
* هذا الأسلوب ينقّح الفهم لمتطلبات البرنامج ويخفض احتمالية العيوب المستقبلية (Defect Debt).

---

### Acceptance Criteria / معايير القبول

**Definition:**

* A clear, documented list of conditions, metrics, and basic constraints that must be met and achieved.
* For software outputs and products to be accepted from the development team.

**التعريف:**

* قائمة واضحة وموثقة بالشروط والمقاييس والقيود الأساسية (بما فيها متطلبات الأداء العالي) التي يجب الوفاء بها وتحقيقها.
* ليتم الموافقة على استلام المخرجات والمنتجات البرمجية من فريق التطوير.

---

### Assertions / التأكيدات البرمجية

**Definition:**

* Programming instructions common in writing tests, requiring the program to verify specific logical conditions.
* Assert that the result must match a specified value - otherwise execution stops or the test fails.

**التعريف:**

* تعليمات برمجية شائعة في كتابة الاختبارات، تُلزم البرنامج بالتحقق من شروط منطقية محددة.
* وتؤكد وجوب أن تكون النتيجة مطابقة لقيمة محددة، وإلا توقف التنفيذ أو فشل الاختبار.

---

<div align="center">
  
**إدارة المشاريع والمنهجيات التقليدية**

## Project Management

</div>

### Stakeholders / أصحاب المصلحة / المعنيون بالمشروع

**Definition:**

* All entities, organizations, and individuals, internal or external, who directly or indirectly influence the project or are affected by its decisions and outputs.
* A stakeholder management plan ensures their engagement and support for work stability.

**التعريف:**

* كافة الكيانات والمنظمات والأفراد، الداخليين أو الخارجيين، الذين يؤثرون بطريقة مباشرة أو غير مباشرة على المشروع أو يتأثرون بقراراته ومخرجاته.
* خطة إدارة هؤلاء المعنيين تضمن تفعيل التزامهم ودعمهم لاستقرار العمل.

---

### KPI - Key Performance Indicator / مؤشر الأداء الرئيسي

**Definition:**

* Explicit quantitative or qualitative metrics and statistics used to measure the level and efficiency of progress made toward achieving strategic objectives.
* Monitors real performance deviations from the planned path.

**التعريف:**

* مقاييس وإحصائيات رقمية أو نوعية صريحة تُستخدم لقياس مستوى وكفاءة التقدم المُنجز في المشروع نحو تحقيق أهدافه الاستراتيجية.
* ومراقبة انحرافات الأداء الحقيقية عن المسار المخطط له.

---

### Roadmap / خارطة الطريق

**Definition:**

* A strategic and visual planning and communication tool showing at a high level the direction and vision of the project for the future.
* Highlights key milestones for the product development journey, without going into daily operational task details.

**التعريف:**

* أداة تخطيط واتصال استراتيجية وبصرية توضح بشكل رفيع المستوى اتجاه ورؤية المشروع للمستقبل.
* والمحطات الأساسية لرحلة تطوير المنتج، دون الدخول في التفاصيل الدقيقة للمهام التشغيلية اليومية.

---

### Milestone / حجر الأساس / معلَم بارز

**Definition:**

* A strategic and critical time point within the project timeline.
* Does not require time in itself, but signals the completion of a core phase or delivery of a major work package.

**التعريف:**

* نقطة زمنية استراتيجية وحاسمة ضمن الجدول الزمني لمراحل المشروع.
* لا تتطلب وقتاً بحد ذاتها، بل تدل وتؤشر على استكمال مرحلة جوهرية أو تسليم حزمة أعمال كبرى.

---

### Scope / النطاق

**Definition:**

* The precise total sum of all outputs, products, services, and processes required to be executed to complete an integrated project.
* Must meet the desired objectives and allocated budget.

**التعريف:**

* المجموع الكلي الدقيق لجميع المخرجات، المنتجات، الخدمات والعمليات المطلوب تنفيذها لإكمال وإنجاز مشروع متكامل.
* يلبي الأهداف المرجوة والميزانية المرصودة.

---

### Scope Creep / زحف النطاق / توسع النطاق

**Definition:**

* The continuous, gradual, and dangerous change and expansion in project requirements or specifications.
* Without undergoing a formal Change Control process and without a parallel adjustment to time and budget.
* Threatens to derail the entire project.

**التعريف:**

* التغيير والتوسع التدريجي المستمر والخطير في متطلبات أو مواصفات المشروع.
* دون الخضوع لعملية رقابة رسمية (Change Control) ودون إجراء تعديل موازٍ للوقت والميزانية.
* مما يهدد بنسف المشروع بأكمله.

> [!CAUTION]
> Scope Creep is the #1 killer of projects. Every undocumented "small addition" has a cost - make sure every change goes through a formal Change Request process.
>
> زحف النطاق هو القاتل الأول للمشاريع. كل "إضافة صغيرة" غير موثقة لها ثمن - تأكد من أن كل تغيير يمر عبر عملية Change Request رسمية.

---

### Deliverables / التسليمات / مخرجات المشروع

**Definition:**

* All unique products, results, tangible and intangible documents, and services that the project is required to deliver.
* To complete a milestone phase or close a project contract.

**التعريف:**

* جميع المنتجات والنتائج الفريدة أو المستندات الملموسة وغير الملموسة والخدمات التي يُلزم المشروع بتقديمها.
* لإتمام مرحلة مرحلية أو إغلاق تعاقد المشروع.

---

### Requirements Management / إدارة المتطلبات

**Definition:**

* An institutional approach aiming to accurately document, analyze, track, and fulfill the expectations and specifications of stakeholders.
* Throughout the entire lifecycle of system or software project execution to ensure no deviation.

**التعريف:**

* نهج ونظام مؤسسي يهدف إلى توثيق، تحليل، تتبع وتلبية توقعات ومواصفات ورغبات أصحاب المصلحة بدقة.
* طوال دورة حياة تنفيذ النظام أو المشروع البرمجي لضمان عدم الانحراف.

---

### Business Case / حالة العمل / جدوى الأعمال

**Definition:**

* The foundational written document motivating the launch of a project.
* Studies the logical reasons behind launching the project and evaluates the required resources against the expected strategic benefits and returns.

**التعريف:**

* الوثيقة الأساسية المكتوبة التي تحفز إطلاق مشروع ما.
* حيث تقوم بدراسة الأسباب المنطقية وراء إطلاق المشروع وتقييم الموارد المالية والبشرية المطلوبة مقابل الفوائد والعوائد الاستراتيجية المتوقعة.

---

### Baseline / الخط المرجعي / خط الأساس

**Definition:**

* The approved base plan (in cost, schedule, or requirements) used as a fixed reference point.
* For comparing and analyzing the degree of actual project performance progress to identify any deviation from the path.

**التعريف:**

* الخطة الأساسية المعتمدة (في التكلفة، أو الجدول الزمني، أو المتطلبات) التي يتم اتخاذها كمرجعية ثابتة.
* لمقارنة وتحليل مدى تقدم أداء المشروع الفعلي لتحديد أي انحراف عن المسار.

---

### Waterfall Methodology / منهجية الشلال

**Definition:**

* The traditional project management methodology; completely linear and sequential.
* Cannot move to the next phase until the previous one is finished.
* Best for systems with very clear and stable requirements that rely on strict documentation.

**التعريف:**

* المنهجية التقليدية لإدارة المشاريع؛ تتميز بكونها خطية ومتسلسلة بالكامل.
* حيث لا يمكن الانتقال لمرحلة تالية إلا بعد إنهاء المرحلة السابقة.
* تُعتبر الأفضل للأنظمة ذات المتطلبات شديدة الوضوح والثبات والتي تعتمد توثيقاً صارماً.

---

### Escalation / التصعيد

**Definition:**

* A decisive administrative procedure taken when the project team is unable to resolve a major obstacle.
* The authority to resolve it is transferred to higher interventional management levels to avoid losses.

**التعريف:**

* إجراء إداري حاسم يتم اتخاذه عند عجز فريق المشروع عن حل عائق رئيسي.
* فيتم نقل صلاحية حله أو التحذير منه للمستويات الإدارية العُليا التدخلية لتجنب الخسائر.

---

### Accountability / المحاسبية / المساءلة

**Definition:**

* An ethical and organizational commitment that holds a specific person fully responsible for the success or failure of an activity or project.
* And the necessity of explaining results - it cannot be delegated to others.

**التعريف:**

* التزام أخلاقي وتنظيمي يُحمل شخصاً بعينه المسؤولية التامة عن نجاح أو إخفاق نشاط أو مشروع.
* وضرورة تفسيره للنتائج، ولا يمكن تفويضها للآخرين.

---

### Constraint / قيد / محدد

**Definition:**

* External and coercive organizational factors that restrict and limit the course of decision-making in the project.
* Narrow the project manager's options. Traditionally include: **Time**, **Cost**, and **Scope** constraints.

**التعريف:**

* العوامل الخارجية والتنظيمية القهرية التي تقيد وتحدد مسار اتخاذ القرارات في المشروع.
* وتضيق خيارات مدير المشروع. وتشمل تقليدياً: قيود **الوقت**، و**التكلفة**، و**نطاق الموارد** المتاحة.

---

<div align="center">
  
**منهجيات التطوير المرنة**

## Agile Methodologies

</div>

### Agile Methodology / منهجية أجايل / المنهجية المرنة

**Definition:**

* A comprehensive umbrella and approach for software management and development.
* Focuses strongly on rapid, early, and continuous delivery of real value to the customer.
* Encourages human interaction and accepts large changes in requirements even in late project stages.

**التعريف:**

* مظلة ومقاربة شاملة لإدارة وتطوير البرمجيات.
* تُركز بقوة على التسليم السريع والمبكر والمستمر لقيم حقيقية للعميل.
* وتشجع التفاعل البشري وتتقبل التغيرات الكبيرة في المتطلبات حتى في المراحل المتأخرة من المشروع.

---

### Agile Manifesto / بيان الأجايل / البيان المرن

**Definition:**

* A formal declaration of the four Agile values and principles.
* Formed a revolution in software engineering by directing the compass toward collaboration, focusing on actual work, and flexibility of strategic planning in response to stakeholder needs.

**التعريف:**

* إعلان رسمي لقيم ومبادئ الأجايل الأربعة.
* الذي شكّل ثورة في هندسة البرمجيات بتوجيه البوصلة نحو التعاون، التركيز على العمل الفعلي، ومرونة التخطيط الاستراتيجي استجابة لاحتياجات أصحاب المصلحة.

---

### Scrum Framework / إطار سكروم

**Definition:**

* A central and flexible working framework in Agile projects enabling teams to manage complex problems.
* By dividing the large project into small iterative cycles to maximize product value with superior productivity and minimize failure rates.

**التعريف:**

* إطار عمل مرن ومركزي في مشاريع الأجايل يُمكن الفرق من إدارة المشاكل المعقدة.
* عبر تقسيم المشروع الكبير إلى دورات تكرارية دقيقة لتعظيم قيمة المنتج بإنتاجية فائقة وتقليل نسب الإخفاق.

---

### Sprint / السبرنت / دورة العمل القصيرة

**Definition:**

* A strictly fixed time frame (usually ranging from one week to four weeks maximum).
* During which the execution team must complete and deliver a finished, operational version of project tasks to present to stakeholders.

**التعريف:**

* إطار زمني محدد وثابت بصرامة (غالباً يمتد من أسبوع واحد إلى أربعة أسابيع كحد أقصى).
* يجب خلاله على فريق التنفيذ إكمال وإخراج نسخة منجزة وقابلة للتشغيل من مهام المشروع لعرضها على أصحاب المصلحة.

---

### Product Backlog / قائمة منتج المشروع

**Definition:**

* The main and vital comprehensive record containing a list of all requirements, features, and software fixes that must be implemented in the future.
* Subject to constant prioritization based on priority and market changes.

**التعريف:**

* السجل الرئيسي والحيوي الشامل الذي يضم قائمة بكافة المتطلبات والميزات والإصلاحات البرمجية التي يجب تنفيذها مستقبلاً.
* ويخضع للترتيب الدائم حسب الأولوية وتغيرات السوق.

---

### Sprint Backlog / قائمة مهام السبرنت

**Definition:**

* A precise sub-list whose specific elements are selected from the "Product Backlog" during the planning meeting.
* To be committed to developing and converting into a finished product during the current sprint cycle and distributing its tasks to the team.

**التعريف:**

* قائمة فرعية دقيقة تختار عناصرها المحددة من "قائمة المنتج" خلال اجتماع التخطيط.
* ليتم التعهد والالتزام بتطويرها وتحويلها لمنتج منتهٍ خلال دورة السبرنت الحالية وتوزيع مهامها على الفريق.

---

### Daily Scrum / Stand-up / الاجتماع اليومي / لقاء الوقوف

**Definition:**

* A very short synchronization meeting (usually no more than 15 minutes), held daily by the execution team.
* To coordinate and share task status, and identify any Impediments that may slow down sprint task list completion.

**التعريف:**

* لقاء تزامن زمني ومكاني قصير جداً (لا يتجاوز عادة 15 دقيقة)، يُجريه فريق التنفيذ يومياً.
* لتنسيق ومشاركة حالة المهام، ورصد أي عقبات (Impediments) قد تواجه الأعضاء وتبطئ من سرعة إنجاز قائمة مهام السبرنت.

---

### Product Owner / مالك المنتج

**Definition:**

* A pivotal role in the Agile environment.
* The person representing the customer's voice and solely responsible for defining the vision, increasing ROI, and ordering and managing project product lists completely.

**التعريف:**

* دور محوري في بيئة أجايل.
* هو الشخص الممثل لصوت العميل والمسؤول الأوحد عن تحديد الرؤية وزيادة العائد على الاستثمار، وعن ترتيب المهام وإدارة وصيانة قوائم منتج المشروع بشكل كامل.

---

### Scrum Master / خبير سكروم / الميسر

**Definition:**

* The Servant-Leader of the team and process facilitator.
* Their core role lies in ensuring strict adherence to Scrum framework rules, removing external challenges, and protecting the development team from distraction.

**التعريف:**

* القائد الخادم (Servant-Leader) للفريق وميسر العمليات.
* يكمن دوره الجوهري في ضمان الالتزام الصارم بتطبيق قواعد إطار سكروم، وإزالة وحل أي تحديات خارجية وحماية فريق التطوير من التشتت.

---

### Kanban / منهجية كانبان / اللوحات المرئية

**Definition:**

* A prominent visual tool in managing Agile work streams.
* Works through visual boards and columns to shed detailed light on task flow progression and measure work efficiency.
* Signals urgently to any bottleneck in delivery processes.

**التعريف:**

* أداة مرئية بارزة في إدارة مسارات أعمال الأجايل.
* تعمل عبر لوحات وأعمدة بصرية لتسليط الضوء الدقيق على تدرج تدفق المهام وقياس كفاءة العمل.
* وللإشارة العاجلة إلى أي اختناق في عمليات التسليم.

---

### Bottleneck / اختناق / عنق الزجاجة

**Definition:**

* A specific point or single step in a workflow where the load is significantly higher than the absorptive capacity of that path.
* Limits and constrains the total production speed of the entire system or team.

**التعريف:**

* نقطة محددة أو خطوة مفردة في مسار سير العمل يكون فيها العبء أعلى بكثير من طاقة أو سرعة القدرة الاستيعابية لذلك المسار.
* مما يحد ويقيد إجمالي سرعة إنتاج النظام أو الفريق بأكمله.

---

<div align="center">
  
**التوجهات المستقبلية: البيانات والذكاء الاصطناعي**

## Future Trends

</div>

### Artificial Intelligence - AI / الذكاء الاصطناعي

**Definition:**

* A category of complex software systems that simulate and replicate human mental capabilities.
* Including perception, reasoning, and problem solving - with the ability to self-train continuously to improve operational outputs.

**التعريف:**

* فئة من النظم البرمجية المعقدة التي تحاكي وتماثل القدرات الذهنية البشرية.
* من حيث الإدراك، والاستنتاج، وحل المشكلات، بل والقدرة على التدرب الذاتي المستمر لتحسين المخرجات التشغيلية.

---

### Big Data / البيانات الضخمة

**Definition:**

* Massive accumulations of database streams (structured and unstructured).
* Characterized by their variety, speed of generation, and enormous volume that defies traditional tools to process.
* Plays a major role in decision-making analytics.

**التعريف:**

* التراكمات الهائلة من تدفقات قواعد البيانات (المنظمة وغير المنظمة).
* التي تتسم بتنوعها وسرعة تولدها وحجمها العاتي الذي يستعصي على أي أدوات تقليدية التعامل معه.
* وتلعب دوراً في تحليلات اتخاذ القرار.

---

### Business Intelligence - BI / ذكاء الأعمال

**Definition:**

* Integrating technological infrastructure and applications with systematic practices to collect, analyze, and visually present large historical and current organizational data.
* To form intelligent tactical decisions for executive departments.

**التعريف:**

* دمج البنى التحتية والتطبيقات التكنولوجية مع الممارسات المنهجية لتجميع وتحليل وعرض بيانات المنشأة الضخمة التاريخية والحالية بشكل مرئي.
* لتشكيل قرارات تكتيكية ذكية للإدارات التنفيذية.

---

### Blockchain / سلسلة الكتل / تقنية البلوك تشين

**Definition:**

* A decentralized ledger or database preserving transaction sequences in the form of digitally interlinked blocks encrypted with strict security.
* Prevents any centralized tampering and guarantees complete reliability and transparency for all parties.

**التعريف:**

* دفتر أستاذ أو قاعدة بيانات غير مركزية، تحفظ تسلسل المعاملات بصيغة كتل رقمية مترابطة مشفرة بأمان صارم.
* بحيث تمنع أي تلاعب مركزي وتضمن الموثوقية التامة والشفافية للأطراف.

---

*تم إعداد هذا القاموس كمرجع شامل لتوحيد المصطلحات التقنية في بيئات العمل العربية والدولية.*

---

## ⭐ Support This Dictionary / ادعم هذا القاموس

If this dictionary helped you understand software engineering terminology or improve your communication with your technical team, consider giving it a **star** ⭐ - it takes 2 seconds and means a lot!

إذا أفادك هذا القاموس في استيعاب المصطلحات التقنية أو تحسين تواصلك مع فريقك التقني، لا تتردد في منحه **Star** ⭐ - لن يأخذ منك سوى ثانيتين وسيحدث فرقًا كبيرًا!

> **Share it** with your team members, project managers, or fellow developers to unify technical language at work.
>
> **شاركه** مع زملائك في الفريق، مديري المشاريع، أو المطورين لتوحيد لغة العمل التقنية.
