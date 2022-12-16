# password_hack
پروژه هک از طریقRainbow

از شما انتظار می رود در این دوره بتوانید پروژه هک را انجام دهید ؛ شما یک فایل csv در اختیار دارید که به دو بخش تقسیم شده است . یک بخش از آن اسم و بخش دیگر یک hash از password است .

hash یک تابع یک طرفه است که براساس ورودی x خروجی y را می دهد. اما هیچ فرمول ریاضی وجود ندارد که بتوانید ازy  بهx  برسید . کاربرد آن این است که شما یک چیزی را hash می کنید و بهy  می رسید  .

اگر یکی تابع x را هک کند، به password واقعی شما نمی رسد. ما تابع مختلفی برای hash داریم. هرکدام از تابع های hash به فرم خاصی کار می‌کند. (به‌ عنوان نکته : همه ی پسورد ها 4 رقمی هستند و ارقام ‌می‌توانند اعداد 0 تا 9 باشند. همچنین ما می‌دانیم که از الگوریتم sha256  برای hash کردن استفاده شده است.) پس انتظار می‌رود که بتوانید این فایل را باز کنید و اطلاعات فایل را جداسازی کرده و نام و پسورد مربوط به آن را مشخص کنید. در واقع کافی است یک حلقه for بنویسید که مثلا از  0-9999 کار کند. هر دفعه عدد مورد نظر را با الگوریتم فوق رمزگذاری کند و یک رشته برمی‌گرداند و این رشته را رمزهای داده شده در فایل مقایسه کند و در صورت برابر بودن عدد نظیر این رشته را به عنوان رمز در خروجی ذخیره کند.

در این پروژه انتظار می رود با جستجو در وب بتوانید نحوه کار کردن با الگوریتم sha256 را یاد بگیرید.

به این روش هک کردن از طریق رنگین کمان ( Rainbow ) می‌‎گویند.
