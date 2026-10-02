# Progress

## Day 0 ✅ (Score: 9/10)
- الأدوات منصبة: .NET 10 (10.0.401), Visual Studio, VS Code, SQL Server, SSMS, Postman, Git 2.55
- أتقنت: git add / commit / push
  - add = يحط التغييرات بالـ Staging
  - commit = يحفظها على جهازي
  - push = يرفعها على GitHub
- عملت أول commit و push ناجح (notes.txt)
- Day 1 (C# basics) تم تجاوزه، أساسياته معروفة

## لسا ضعيف
- ما في شي حاليًا. (ملاحظة: اسم الـ repo .NET_TRAINING، ممكن أغيره لـ StudentManagementApi)

## وين وقفنا
- التالي: Day 2 (OOP)
## Day 2A ✅ (Score: 9/10)
- أتقنت: Classes & Objects, Properties, Encapsulation (private field + validation بالـ set)
- PascalCase للـ Classes والـ Properties
- decimal للفلوس (مع m)
- غلطات تكررت وصححتها: أسماء بحروف صغيرة، اسم parameter غلط، حالة أحرف الـ strings

## لسا ضعيف
- انتباه للتفاصيل الصغيرة (أسماء، حروف، ;) - اقرأ الكود قبل ما تشغله

## وين وقفنا
- التالي: Day 2B (Inheritance, Polymorphism, Interfaces)
## Day 2B ✅ (Score: 10/10)
- أتقنت: Inheritance (Person → Student/Teacher/Admin)، Polymorphism (virtual/override)، List<Person> مع foreach
- أتقنت: Interfaces كعقد (contract)، List<IDiscountable> فيها classes مختلفة
- Object Initializer: new Student { Id = 1, Name = "Ammar" }
- بدون أخطاء بهالجلسة، PascalCase واسم الـ parameters مضبوطين

## لسا ضعيف
- Multiple Interfaces (class ينفذ أكثر من interface) لسا ما جربته
- تجربة حذف method من class ينفذ interface (قراءة رسالة Error) لسا ما اتعملت
- انتباه للتفاصيل الصغيرة (أسماء، حروف، ;) - اقرأ الكود قبل ما تشغلهgit 

## وين وقفنا
- التالي: نكمل تمارين Interfaces المعلقة (IPrintable + total discount + تجربة الـ Error)، وبعدها Quiz على Day 2B، وبعدين Day 3 (Collections + LINQ)
## Day 2B ✅ (Score: 10/10)
- أتقنت: Inheritance (:), virtual/override (Polymorphism), Interfaces (I + implements)
- فهمت الفرق: class يرث من class واحد بس، بس يقدر يطبق كذا interface
- مثال مطبق: Employee -> Manager (override CalculateBonus) + IReportable

## لسا ضعيف
- ما في شي واضح، بس تذكر تكتب object creation وتستدعي الـ methods فعليًا مش بس تعرّف الـ classes

## وين وقفنا
- Day 2 (OOP) خلص بالكامل ✅
- التالي: Day 3 (Collections + LINQ + مقدمة async/await)
## Day 3 ✅ (Score: 10/10)
- أتقنت: List<T>, Dictionary<TKey,TValue>, LINQ (Where, Select, OrderBy, FirstOrDefault, Count) مع Chaining
- فهمت Lambda expressions (n => n > 10)
- أخذت مقدمة بسيطة لـ async/await (رح نتعمق فيها مع EF Core بـ Day 12)

## لسا ضعيف
- ما في شي واضح، أداء ممتاز اليوم كامل

## وين وقفنا
- Day 3 خلص بالكامل ✅
- التالي: Day 4 (SQL 1: SELECT, WHERE, AND/OR, ORDER BY, LIKE, IN, BETWEEN)
## Day 4 ✅ (Score: 10/10)
- أتقنت: SELECT, WHERE, ORDER BY (ASC/DESC), LIKE ('A%'), IN, BETWEEN
- قدرت أدمج كذا شرط مع بعض (AND + IN + ORDER BY) بنفس الـ query
- أداء ممتاز، ما في أخطاء

## لسا ضعيف
- ما في شي واضح

## وين وقفنا
- Day 4 خلص بالكامل ✅
- التالي: Day 5 (SQL 2: INSERT, UPDATE, DELETE, COUNT/SUM/AVG/MIN/MAX, GROUP BY, HAVING)
## Day 5 ✅ (Score: 10/10)
- أتقنت: INSERT, UPDATE, DELETE (مع أهمية WHERE عشان ما نعدل/نمسح كل الجدول)
- أتقنت: Aggregate Functions (COUNT, SUM, AVG, MIN, MAX)
- أتقنت: GROUP BY (تقسيم الصفوف لمجموعات + تطبيق aggregate على كل مجموعة)
- أتقنت: HAVING (فلترة بعد الـ GROUP BY) والفرق بينه وبين WHERE
- قاعدة مهمة اتعلمتها: أي عمود بالـ SELECT لازم يكون بالـ GROUP BY أو جوا aggregate function

## لسا ضعيف
- ما في شي واضح، أداء ممتاز اليوم كامل (10/10 بكل التمارين)

## وين وقفنا
- Day 5 خلص بالكامل ✅
- التالي: Day 6 (SQL 3: Primary/Foreign Keys, Relationships, Normalization basics, INNER JOIN, LEFT JOIN)
## Day 6 ✅ (Score: 9/10)
- أتقنت: Primary Key, Foreign Key (يشاور على PK بجدول تاني)
- أتقنت: One-to-Many (Major->Students), Many-to-Many (يحتاج جدول وسيط)
- أتقنت: INNER JOIN (بس المتطابق), LEFT JOIN (كل اليسار + NULL لو ما فيه تطابق)
- خطأ واحد: قلت إن FK لازم يكون Unique (غلط - ممكن يتكرر بجدول Many side)

## لسا ضعيف
- تمييز نظري بين INNER/LEFT/FULL JOIN بأسئلة Multiple Choice (مش بالكتابة)

## وين وقفنا
- Day 6 خلص بالكامل ✅
- التالي: Day 7 (SQL Practice - تمارين واقعية تجمع كل SQL)
## Day 7 ✅ (Score: 10/10)
- أتقنت: تمارين SQL مركبة (JOIN + WHERE + GROUP BY + HAVING + ORDER BY)
- أتقنت: LEFT JOIN مع COUNT(Students.Id) عشان Major بدون طلاب يطلع 0
- أتقنت: Subqueries (correlated subquery، >= ALL، AVG)
- أتقنت: IS NULL / IS NOT NULL (مش = NULL)
- انتبه: GROUP BY بيعمل مجموعة للـ NULL كمان

## لسا ضعيف
- ما في شي واضح. تذكر تجاوب كل أسئلة الـ Quiz (نسيت س1 و س2 أول مرة)

## وين وقفنا
- Day 7 خلص بالكامل ✅ (SQL كامل)
- التالي: Day 8 (ASP.NET Core Fundamentals: Project structure, Program.cs, Dependency Injection, Middleware, Configuration)
## Day 8 (جزئي) ✅ (Score: 8/10)
- أتقنت: Project structure، Program.cs (Services قبل Build، Middleware بعده)
- أتقنت: Dependency Injection + Interface (IStudentService) وتبديل الـ implementation بسطر وحد
- أتقنت: Lifetimes: Singleton (1,2,3..)، Scoped (1,1,1 لكل Request)، Transient
- أتقنت: Middleware (app.Use، await next()، short-circuit، ترتيب Authentication قبل Authorization)
- فهمت: Unable to resolve service = نسيت التسجيل بالـ DI

## لسا ضعيف
- صيغة الـ generics: AddScoped<IA, A>() (backticks بالنسخ، الفاصلة، الـ >)
- انتباه لحالة الأحرف ("Hello Ammar")
- تجاوب كل التمارين بالرسالة (تمارين 16/17 تأجلت)
- الفرق الحقيقي بين Scoped و Transient (لما أكثر من class يطلبوا نفس الـ Service)

## وين وقفنا
- Day 8 باقي منه: Configuration (appsettings.json، IConfiguration، GetConnectionString) + تمارينه
- التالي بعدها: Day 9 (HTTP + Web API)
