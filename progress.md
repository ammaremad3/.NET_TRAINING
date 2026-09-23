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