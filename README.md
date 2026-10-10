# AliLang — برنامه‌نویسی پایتون به فارسی 


## اجرا

###### It works like VS Code: simply write your code and hit run! 
After writing the code in Persian according to the instructions, you can view the actual code in the Python environment with just a single click.
## کلیدها در پنجره
F5 اجرا | Shift+F5 توقف | Ctrl+S ذخیره | Ctrl+O باز کردن


## نکته‌ها
- رشته‌ها و کامنت‌ها دست‌نخورده می‌مانند؛ اعداد فارسی (۱۲۳)، ویرگول فارسی (،) و ممیز فارسی (٫) خارج از رشته‌ها خودکار تبدیل می‌شوند.
- نیم‌فاصله در نام متغیرها به `_` تبدیل می‌شود (می‌شود → می_شود).
- کلمات رزروشده (مثل طول، مجموع، زمان) را به‌عنوان نام متغیر استفاده نکن، وگرنه با تابع هم‌نامش قاطی می‌شود.
- فایل `ابزار.ali` را می‌شود با `واردکن ابزار` در فایل دیگر وارد کرد.
- برای تغییر نام زبان و پسوند فایل: ثابت‌های `LANG_NAME` و `FILE_EXTENSION` بالای `ali_lang.py`.
- برای افزودن کلمه‌ی جدید فقط یک خط به دیکشنری `KEYWORDS` اضافه کن.
