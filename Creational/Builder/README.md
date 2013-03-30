
#الگوی طراحی Builder

تعریف: الگوی طراحی Builder، روند ساخت یک شیء پیچیده را از نمایش آن جدا می‌کند به طوری که یک روند ساخت مشترک می‌تواند برای ساخت انوع نمایش‌ها به کار گرفته شود.

مثال: فرض کنید بخواهیم انواع و اقسام خانه‌ها را طراح کنیم. روند طراحی در تمامی خانه‌ها یکسان است. که به کلاس‌های زیر تقسیم می‌شود:

##Builder
1. زیربنای آن را ایجاد می‌کنیم.
2. ساختار و اسکلت آن را ایجاد می‌کنیم.
3. سقف آن را می‌سازیم.
4. فضای داخل خانه را طراحی می‌کنیم.

بنابراین برای طراحی همهٔ ساختمان‌ها یک رویهٔ یکسان داریم. بنابراین یک کلاس اینترفیس برای تمامی ساختمان‌ها با ۴ رویهٔ مذکور ایجاد می‌کنیم. که به آن Builder می‌گوییم.

در این مثال: HouseBuilder

## ConcreateBuilder
حال به تعداد انواع خانه‌ها، اینترفیس Builder را پیاده‌سازی می‌کنم، در این مثال می‌توانیم خانهٔ خشتی، خانهٔ گلی، خانهٔ برفی، خانهٔ فلزی، خانهٔ فلزی، خانهٔ چوبی، خانهٔ سیمانی را بسازیم. به هر یک از این کلاس‌ها ConcreateBuilder می‌گوییم:

1. KheshtiBuilder
2. GeliBuilder
3. BarfiBuilder
4. FeleziBuiler

## Director
پیمانکار ساختمان، ساختمان‌ها را از طریق اینترفیس House ایجاد می‌کند. (ورودی: یک نوع خانه از نوع HouseBuilder)

1. ساخت زیربنا
2. ساخت اسکلت و ساختار ساختمان
3. ساخت سقف
4. طراحی درون ساختمان
## Product
محصول نهایی، حاصل ترکیب تمامی مراحل ساخت یک خانه است.
1. خانهٔ گلی
2. خانهٔ خشتی
3. خانهٔ سیمانی
و ...

## Client
HouseBuilder builder = new KheshtiBuilder();
Director director = new Director(builder);
director.construct();

بیشتر بخوانید:
1. http://javapapers.com/design-patterns/builder-pattern/

