![SSMS-Banner](https://github.com/cc-Mehdi/SSMS-Guide/assets/57840939/2b6c2f56-6148-44fe-84bd-24acc8b9022b)


# راهنمای SSMS


#### SSMS (SQL Server Management Studio):

یک ابزار قدرتمند و جامع است که توسط مایکروسافت برای مدیریت پایگاه داده های Microsoft SQL Server توسعه یافته است. این راهنما یک نمای کلی از ویژگی‌ها و عملکردهای کلیدی SSMS را ارائه می‌کند که هدف آن کمک به مدیران پایگاه داده، توسعه‌دهندگان و تحلیلگران در کار مؤثر با پایگاه‌های داده SQL Server است.

این راهنما زمینه های اصلی زیر را پوشش می دهد:


1.**نصب و راه اندازی:** راهنما با دستورالعمل های گام به گام در مورد نحوه دانلود، نصب و پیکربندی SSMS در رایانه شما شروع می شود. الزامات سیستم را تشریح می کند و راهنمایی برای اتصال به نمونه های SQL Server ارائه می دهد.
   
2.**نمای کلی رابط:** رابط کاربری SSMS شامل Object Explorer، Query Editor، Solution Explorer و پنجره های ابزار مختلف مورد بررسی قرار می گیرد. کاربران یاد می گیرند که چگونه با رابط آن کار کنند و رابط کاربری آن را درک کنند.

3.**اتصال به پایگاه های داده:** راهنما نحوه اتصال به نمونه های محلی و راه دور SQL Server را توضیح می دهد. این روش‌های مختلف احراز هویت، مانند احراز هویت ویندوز و احراز هویت SQL Server، و نحوه ذخیره تنظیمات اتصال برای راحتی را پوشش می‌دهد.

4.**مدیریت پایگاه داده:** کاربران با وظایف مربوط به مدیریت پایگاه داده مانند ایجاد، اصلاح و حذف پایگاه داده ها، جداول، نماها و سایر اشیاء پایگاه داده آشنا می شوند. آنها یاد می گیرند که چگونه از Object Explorer برای مرور و دستکاری طرح های پایگاه داده استفاده کنند.

5.**کوئری و اسکریپت نویسی:** ویرایشگر کوئری جزء مرکزی SSMS برای نوشتن و اجرای کوئری های SQL است. راهنما نحوه نوشتن و اجرای کوئری ها، استفاده از قطعه کد و تولید اسکریپت برای اشیاء پایگاه داده را نشان می دهد.

6.**بهینه سازی کوئری:** این راهنما بینش هایی را در مورد تکنیک های بهینه سازی عملکرد کوئری ارائه می دهد، از جمله تجزیه و تحلیل طرح های اجرای کوئری، استراتژی های نمایه سازی، و استفاده از ابزارهای تنظیم عملکرد داخلی.

7.**پشتیبان گیری و بازیابی:** کاربران یاد می گیرند که چگونه با استفاده از SSMS پشتیبان گیری و بازیابی پایگاه داده را انجام دهند. این شامل ایجاد فایل‌های پشتیبان، زمان‌بندی پشتیبان‌گیری و بازیابی پایگاه‌های داده از پشتیبان‌گیری می‌شود.

8.**مدیریت امنیت:** راهنما مدیریت کاربر و مجوزها را پوشش می‌دهد و نحوه ایجاد لاگین، اختصاص نقش‌ها و اعطای مجوز به کاربران و گروه‌ها را نشان می‌دهد.

9.**تعمیر و نگهداری و نظارت:** کاربران با ابزارها و ویژگی های نظارت بر سلامت پایگاه داده، شناسایی تنگناها و عیب یابی مشکلات آشنا می شوند. وظایفی مانند بررسی یکپارچگی پایگاه داده، مدیریت مشاغل و نظارت بر فعالیت ها پوشش داده شده است.

10.**یکپارچه سازی با کنترل منبع:** راهنما به نحوه ادغام SSMS با سیستم های کنترل نسخه مانند Git اشاره می کند و به توسعه دهندگان اجازه می دهد تغییرات در طرح و اشیاء پایگاه داده را ردیابی کنند.

11.**برنامه های افزودنی و سفارشی سازی:** SSMS از برنامه های افزودنی و سفارشی سازی برای افزایش عملکرد پشتیبانی می کند. به کاربران نشان داده می شود که چگونه برنامه های افزودنی را نصب کنند و SSMS را مطابق با نیازهای خاص خود تنظیم کنند.

12.**نکات و ترفندها:** راهنما با مجموعه ای از نکات و میانبرها برای بهبود بهره وری و کارایی در حین استفاده از SSMS به پایان می رسد. 

### با پیروی از این راهنما، کاربران می توانند در استفاده از SQL Server Management Studio برای مدیریت مؤثر، توسعه و بهینه سازی پایگاه داده های SQL Server مهارت کسب کنند و وظایف مربوط به پایگاه داده خود را کارآمدتر و ساده تر کنند.


## جدول محتوا
* [نصب و راه اندازی](#installation-and-setup-نصب-و-راه-اندازی)
* [نمای کلی رابط](#interface-overview-نمای-کلی-رابط)
* [اتصال به پایگاه های داده](#connecting-to-databases-اتصال-به-پایگاه-های-داده)
* [مدیریت پایگاه داده](#database-management-مدیریت-پایگاه-داده)
* [کوئری و اسکریپت نویسی](#querying-and-scripting-کوئری-و-اسکریپت-نویسی)
* [بهینه سازی کوئری](#query-optimization-بهینه-سازی-کوئری)
* [پشتیبان گیری و بازیابی](#backup-and-restore-پشتیبان-گیری-و-بازیابی)
* [مدیریت امنیت](#security-management-مدیریت-امنیت)
* [تعمیر و نگهداری و نظارت](#maintenance-and-monitoring-تعمیر-و-نگهداری-و-نظارت)
* [یکپارچه سازی با کنترل منبع](#integration-with-source-control-یکپارچه-سازی-با-کنترل-منبع)
* [برنامه های افزودنی و سفارشی سازی](#extensions-and-customization-برنامه-های-افزودنی-و-سفارشی-سازی)
* [نکات و ترفندها](#tips-and-tricks-نکات-و-ترفندها)


## Installation and Setup (نصب و راه اندازی)

[-Complete Installation Tutorial (Youtube)](https://www.youtube.com/watch?v=ZxSWKEgTjKc)

[-Complete Installation Tutorial (Aparat)](https://www.aparat.com/v/ck8sX)

**--The version that we use for this example is SSMS 2019 Developer Edition--**

To install SQL Server Management Studio (SSMS), follow these steps:

1. Download SSMS: Go to the official Microsoft Download Center and search for "SQL Server Management Studio." Choose the version that is compatible with your system and requirements. Or use this [link](https://soft98.ir/software/programming/3594-%D9%85%D8%A7%DB%8C%DA%A9%D8%B1%D9%88%D8%B3%D8%A7%D9%81%D9%80%D8%AA-%D8%A7%D8%B3-%DA%A9%DB%8C%D9%88-%D8%A7%D9%84-%D8%B3%D8%B1%D9%88%D8%B1.html) to download from a persian web site.

2. Run Installer: Once the download is complete, run the installer executable. It will guide you through the installation process. ![Run Installer](https://github.com/cc-Mehdi/SSMS-Guide/assets/57840939/d130a7ad-d7ff-4b05-8aba-1e6173c8f181)

3. Finish: Once the installation is complete, you'll receive a confirmation message. You can now launch SQL Server Management Studio from your Start menu or desktop shortcut. ![Finish](https://github.com/cc-Mehdi/SSMS-Guide/assets/57840939/b8547d43-2cc0-48d1-8fd7-2d2e5b3924b8)


Remember that the installation process might slightly differ depending on the specific version of SSMS and your system's configuration. Make sure to consult the official documentation or installation guides for any specific details or troubleshooting.

## Interface Overview (نمای کلی رابط)
## Connecting to Databases (اتصال به پایگاه های داده)
## Database Management (مدیریت پایگاه داده)
## Querying and Scripting (کوئری و اسکریپت نویسی)
## Query Optimization (بهینه سازی کوئری)
## Backup and Restore (پشتیبان گیری و بازیابی)
## Security Management (مدیریت امنیت)
## Maintenance and Monitoring (تعمیر و نگهداری و نظارت)
## Integration with Source Control (یکپارچه سازی با کنترل منبع)
## Extensions and Customization (برنامه های افزودنی و سفارشی سازی)
## Tips and Tricks (نکات و ترفندها)





