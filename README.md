Design-Patterns
===============

## Creational Patterns
<div dir="rtl">
- [Abstract Factory](Creational/AbstractFactory): بدون مشخص کردن کلاس‌های کانکرت، واسطی برای ساخت خانواده‌ای از اشیاء وابسته یا مرتبط با یکدیگر فراهم می‌کند.

- [Builder](Creational/Builder): روند ساخت یک شیء پیچیده را از نمایش آن جدا می‌کند به طوری که یک روند ساخت مشترک می‌تواند برای ساخت انوع بازنمایی‌ها به کار گرفته شود.

- [Factory Method](Creational/FactoryMethod): واسطی برای ساخت اشیاء ایجاد می‌کند، اما به زیرکلاس‌ها اجازه می‌دهد که تصمیم بگیرند که چه کلاسی را نمونه‌سازی کنند. این الگو اجازه می‌دهد تا نمونه‌برداری کلاس، به زیرکلاس‌ها معوق شود.

- [Prototype](Creational/Prototype): انواع اشیائی که باید ساخته شوند را با استفاده از یک نمونهٔ اولیه، مشخص می‌کند و اشیاء جدید را با کپی کردن این نمونهٔ اولیه تولید می‌کند.

- [Singleton](Creational/Singleton): تضمین می‌کند که کلاس تنها یک نمونه داشته باشد و دسترسی سراسری برای آن فراهم می‌کند.

<div dir="ltr">

## Structural Patterns
<div dir="rtl">
- [Adapter](Structural/Adapter): یک واسط را به واسط مورد نظر کلاینت تبدیل می‌کند و اجازه می‌دهد تا کلاس‌ها با اینترفیس‌های متفاوت و ناسازگار با یکدیگر کار کنند.

- [Bridge](Structural/Bridge): لایهٔ انتزاع را از لایهٔ پیاده‌سازی جدا می‌کند، بنابراین دو کلاس می‌توانند مستقلاً تغییر کنند.

- [Composite](Structural/Composite): اشیاء را درون ساختار درختی ترکیب می‌کند تا سسله-مراتب جز-کل را ارائه کند. الگوی کامپوزت به کارخواه‌ها اجازه می‌دهد تا با اشیاء تکی و با اشیائی که ترکیبی از اشیاء هستند، به یک صورت رفتار کند.

- [Decorator](Structural/Decorator): وظایف و قابلیت‌های بیشتری را به صورت داینامیک به شیء اضافه می‌کند. دکوریتورها برای توسعهٔ رفتارها و قابلیت‌ها روش انعطاف‌پذیر جایزینی را برای زیرکلاس‌سازی ارائه می‌دهند.

- [Facade](Structural/Facade): واسط یکپارچه‌ای را برای مجموعه‌ای از واسط‌ها در زیر سیستم، ارائه می‌دهد. این الگو واسط سطح-بالاتری را تعریف می‌کند که استفاده از زیرسیستم را ساده‌تر می‌کند.

- [Flyweight](Structural/Flyweight): استفادهٔ دوبارهٔ بسیاری از اشیاء fine-grain را با اشتراک آن‌ها در سیستم، آسان می‌کند.

- [Proxy](Structural/Proxy): برای کنترل دسترسی به اشیاء، نماینده یا نگهدارنده‌ای برای آن‌ها ارائه می‌کند.

<div dir="ltr">

## Behavioural Patterns
<div dir="rtl">
- Chain Of Responsibility(Structural/ChainOfResponsibility): با دادن بیشتر از یک شیء برای هندل کردن درخواست از جفتگری (کوپلینگ) فرستندهٔ درخواست و گیرندهٔ درخواست اجتناب می‌کند. اشیاء گیرنده را زنجیر می‌کند و درخواست را در امتداد زنجیر گذر می‌دهد تا زمانی که یکی از اشیاء آن را هندل کند.

- [Command](Behavioural/Command): درخواست را به عنوان یک شیء کپسوله می‌کند، از این رو اجازه می‌دهد تا بتوانید کارخوه‌ها را با درخواست‌ها، صف‌ها و یا لاگ‌های متفاوت پارامتری کنید.

- [Interpreter](Behavioural/Interpreter): یک بازنمایی برای گرامر زبان داده شده تعریف می‌کند و مفسر توسط این باز نمایی، جملات زبان را تفسیر می کند.

- [Iterator](Behavioural/Iterator): روشی برای دستری به عناصر یک شیء اگریگیت فراهم می‌کند بدون اینکه اصول پیاده‌سازی و ساختمان دادهٔ لایهٔ زیرین اگریگیت را نمایش دهد.

- [Mediator](Behavioural/Mediator): شیء‌ای را تعریف می‌کند که نحوهٔ ارتباط بین مجوعه‌ای از اشیاء را کپسوله می‌کند. این الگو با جلوگیری ارتباط صریح بین اشیاء از جفتگری ضعیف (loose coupling) پشتیبانی می‌کند.

- [Memento](Behavioural/Memento): بدون تخلف از کپسوله‌سازی، وضعیت داخلی شیء ضبط و استخراج می‌کند از این رو شیء بعداً می‌تواند به این حالت برگردد.

- [Observer](Behavioural/Observer): وابستگی یک-به-چند بین اشیاء تعریف می‌کند بنابراین وقتی یک شیء وضعیت‌اش را تغییر می‌دهد، تمامی اشیاء وابسته به آن از آن تغییر مطلع شده و به صورت خودکار به روز می‌شوند.

- [State](Behavioural/State): به شیء این اجازه را می‌دهد که وقتی وضعیت درونی‌اش تغییر کرد، رفتارش را تغییر دهد. به نظر می‌رسد که شیء کلاس خود را عوض می‌کند.

- [Strategy](Behavioural/Strategy): خانواده‌ای از الگوریتم ها را تعریف می‌کند، هر یک را کپسوله می‌کند و آن‌ها را جابه‌جا پذیر می‌کند. الگوی استراتژی اجازه می‌دهد که الگوریتم‌ها مستقل از کارخواهی که از آن‌ها استفاده می‌کند، تغییر کنند.

- [Template Method](Behavioural/TemplateMethod): استخوان‌بندی و شالودهٔ اصلی عملیات الگوریتم را تعریف می‌کند، و پیاده‌سازی هر مرحله را به زیرکلاس‌ها می‌سپارد. این الگو، به زیرکلاس‌ها این اختیار را می‌دهد که تا خودشان، مراحل الگوریتم را پیاده کنند بدون اینکه ساختار الگوریتم را تغییر دهند.

- [Visitor](Behavioural/Visitor): اعمالی که باید روی عناصری از شیء اجرا شود را ارائه می‌کند. این الگو اجازه را می‌دهد تا اعمال جدیدی تعریف کنید بدون اینکه کلاس‌هایی که این اعمال روی آن‌ها انجام می‌شود را تغییر دهید.



