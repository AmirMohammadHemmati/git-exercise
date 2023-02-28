# First_EXERCISE :
## ۱ -گیت چیست و چه کاربردی دارد؟
گیت یکی از محبوبترین سیستم های کنترل ورژن و مورد توجه همه شرکت های بزرگ و کوچک نرم افزاری قرار گرفته است. قابلیت های فراوان گیت راحتی آن در استفاده و دقیق بودن و بی ارور بودن آن از مزایای استفاده از آن است. به صورت  distributed  و OpenSource  طراحی شده. وقتی نام برنامه نویسی سیستمی به گوشمان میخورد یاد لینوکس و هسته آن می افتیم. نحوه کارکرد git از لحاظ syntax دقیقا مثل Linux  است زیرا که نویسنده هر دو سیستم مدیریت فایلی مذکور Linus Torvarlds است. git  در سال ۲۰۰۵ released شد و امروزه بر روی اکثر سیسنم عامل ها و IDEA ها قرار گرفت است.
گیت از سیستم توزیع خوشه‌ای یا درختی استفاده می‌کند. برخلاف برخی از نرم‌افزارهای کنترل ورژن، Git هنگام ذخیره تاریخچه و نسخه‌های فایل، نام فایل‌ها را در نظر نمی‌گیرد و روی محتوای فایل متمرکز است. همچنین، مخزن گیت از ترکیب رمزگذاری دلتا برای ذخیره تفاوت‌های کد استفاده و درادامه با فشرده‌سازی، فایل‌ها را کاملاً ذخیره می‌کند. 
## ۲ - دستور git init چه کاری انجام میدهد ؟
وقتی که میخواهیم یک مخزن یا  Repository  جدید بسازیم از این دستور استفاده میکنیم. به اینگونه که :  اجرای این دستور پوشه‌ای جدید به نام git. در دایرکتوری فعلی شما ایجاد می‌کند. این دستور دایرکتوری (directory) پروژه را آغاز می‌کند
همچنین باید در نظر داشته باشیم که git init دستوری یک‌بارمصرف است که فقط هنگام راه‌اندازی اولیه و ایجاد مخزن جدید استفاده می‌شود.
## ۳ - دستور git status چه کاری انجام میدهد ؟
دلیل وجود دستور git --status در این است که میتوانید فایل‌های موجود در ناحیه مرحله‌بندی و فایل‌های ویرایش‌شده‌ و نیازمند به ثبت را مشاهده کنید.
لازم به ذکر است که در این دستور اطلاعاتی از Commitهای ثبت‌شده را نشان نمی‌دهد و برای نمایش وضعیت بین Git Add و Git Commit استفاده می‌شود. اگر گیت تغییرات فایل‌ها را به‌درستی ردیابی کند، پس از تغییر فایل، باید آن را در Git Status ببینیم.
پس به طور کلی دستور Git Status برای نمایش وضعیت مخزن و ناحیه مرحله‌بندی استفاده می‌شود.
## ۴ - دستور git add چه کاری انجام میدهد ؟
اگر بخواهیم با git add   کار کنیم یعنی میخواهیم اطلاعاتی که برای بارگزاری در فضای گیت خود را به لیست اطلاعات مورد نیاز برای ثبت شدن اضافه کنیم. به طور کلی  دستور add فایل‌هایی را اضافه می‌کند که در خط فرمان مشخص شده‌اند.
هر بار که اطلاعاتی اضافه میکنیم میتوانیم این کار را انجام دهیم. یعنی  دستور git add را می‌توان چندین‌بار قبل از انجام Commit اجرا کرد.  در‌نهایت، همه این فایل‌ها را می‌توان با یک Commit ثبت کرد
## ۵ - دستور git commit چه کاری انجام میدهد ؟
این دستور همان کار ثبت را انجام میدهد. به این گونه که بعد از یک یا چند دستور add مقداری اطلاعات درون فایل مورد نیاز بررسی دستور Commit  قرار میگیرد. وقتی دستور Commit فراخوانی میشود این فایل ها مورد بررسی قرار میگیرند و درون مخزن جای میگیرند.
نکات جالب در مورد این دستور :
کامیت ها مانند عکس فوری از فایل‌ها هستند که به همان صورت ذخیره می‌شوند و هیچ‌گاه تغییردادنی نیستند.
هر Commit در شاخه اصلی مخزن ثبت می‌شود که می‌توانید آن‌ها را ببینید و درصورت نیاز، کدها را بازیابی کنید
 هر Commit حاوی یک commit-id است. این commit-id شماره‌ای رمزنگاری شده است
 ## ۶ - دستور git log چه کاری انجام میدهد ؟
 در مورد دستور git log میتوانیم بگوییم این دستور برای بررسی تغییرات در مخزن استفاده میشود. به این گونه که رکوردی از commit  های ثبت شده به همراه تاریخ عوض شدن یا اضافه شدن ، نام کاربر و ایمیل آن هنگام رخ دادن COMMIT ، عنوان کامیت و کانیت هش.
 ## ۷ - دستور git branch چه کاری انجام میدهد ؟
 دستور git branch نشان میدهد هم اکنون کدام branch در حال استفاده است .
## ۸ - دستور git remote add چه کاری انجام میدهد و چه کاربردی دارد ؟
برای اضافه کردن هر فایل جدید به REPOSITORY مذکور از دستور Remote add استفاه میشود.
این دستور این امکانات را به شما میدهد که شما میتوانید با هر سری تغییراتی که در گیت repository انجام میدهید به طور خودکار آن تغییرات در داخل بستر ارایه دهنده گیت شما قرار گیرند. شما میتوانید به یک remote repository  دسترسی داشته باشید.
## ۹ - دستور git push چه کاری انجام میدهد ؟
دستور git push معمولا برای منتشر کردن تغییر های Local در یک مخزن مرکزی استفاده می شود. پس از این که یک مخزن Local تغییر کرد، دستور push اجرا می شود تا آن تغییر ها با اعضای تیم به اشتراک گذاشته شود.
## ۱۰ - دستور git pull چه کاری انجام میدهد و برای چه استفاده میشود ؟
این دستور برای بیرون کشیدن یا دانلود اطلاعات از remote repository   صورت میگیرد به اینگونه که ابتدا دستوری با نام fetch  را فراخوانی میکند. این دستور اطلاعات را از مخزن دانلود میکند  در ادامه دستور git merge را اجرا میکند. همانطور که ار نام دستور مشخص است باید اطلاعات درون مخزن remote یکی شوند . اینکار از طریق commit merge انجام میشود و حال درون repository local نیز اطلاعات به صورت صحیح مدیریت شدند.
## ۱۱ - دستور git clone چه کاری انجام میدهد و برای چه استفاده میشود ؟
با دستور Clone میتوانیم هرآنچه در مخزن مرکزی قرار گرفته است را Clone  کنیم و به اطلاعات آن فایل ها دسترسی کامل داشته باشیم.
کاربرد این دستور در اتصال به منابعی مانند github بسیار دیده میشود . زیرا با این دستور میتوانیم یک فایل مشابه محلی از فایلهای مخزن آنلاین درست کنیم.