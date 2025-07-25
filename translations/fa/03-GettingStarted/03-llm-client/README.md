<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "f74887f51a69d3f255cb83d0b517c623",
  "translation_date": "2025-07-04T15:47:33+00:00",
  "source_file": "03-GettingStarted/03-llm-client/README.md",
  "language_code": "fa"
}
-->
عالی، برای گام بعدی، بیایید قابلیت‌های سرور را فهرست کنیم.

### -2 فهرست کردن قابلیت‌های سرور

حالا به سرور متصل می‌شویم و قابلیت‌های آن را درخواست می‌کنیم:

### -3- تبدیل قابلیت‌های سرور به ابزارهای LLM

گام بعدی پس از فهرست کردن قابلیت‌های سرور، تبدیل آن‌ها به فرمتی است که LLM بتواند درک کند. وقتی این کار را انجام دادیم، می‌توانیم این قابلیت‌ها را به عنوان ابزار به LLM خود ارائه دهیم.

عالی، حالا آماده‌ایم که درخواست‌های کاربر را مدیریت کنیم، پس بیایید به آن بپردازیم.

### -4- مدیریت درخواست‌های ورودی کاربر

در این بخش از کد، درخواست‌های کاربر را مدیریت خواهیم کرد.

عالی، انجامش دادی!

## تمرین

کد تمرین را بردارید و سرور را با ابزارهای بیشتری توسعه دهید. سپس یک کلاینت با LLM بسازید، مانند تمرین، و آن را با پرامپت‌های مختلف تست کنید تا مطمئن شوید همه ابزارهای سرور شما به صورت داینامیک فراخوانی می‌شوند. این روش ساخت کلاینت باعث می‌شود کاربر نهایی تجربه کاربری بسیار خوبی داشته باشد، چون می‌تواند از پرامپت‌ها استفاده کند، به جای دستورات دقیق کلاینت، و از وجود هر سرور MCP که فراخوانی می‌شود بی‌خبر باشد.

## راه حل

[Solution](/03-GettingStarted/03-llm-client/solution/README.md)

## نکات کلیدی

- افزودن LLM به کلاینت شما راه بهتری برای تعامل کاربران با سرورهای MCP فراهم می‌کند.
- باید پاسخ سرور MCP را به چیزی تبدیل کنید که LLM بتواند آن را درک کند.

## نمونه‌ها

- [ماشین حساب جاوا](../samples/java/calculator/README.md)
- [ماشین حساب .Net](../../../../03-GettingStarted/samples/csharp)
- [ماشین حساب جاوااسکریپت](../samples/javascript/README.md)
- [ماشین حساب تایپ‌اسکریپت](../samples/typescript/README.md)
- [ماشین حساب پایتون](../../../../03-GettingStarted/samples/python)

## منابع اضافی

## مرحله بعد

- بعدی: [استفاده از سرور با Visual Studio Code](../04-vscode/README.md)

**سلب مسئولیت**:  
این سند با استفاده از سرویس ترجمه هوش مصنوعی [Co-op Translator](https://github.com/Azure/co-op-translator) ترجمه شده است. در حالی که ما در تلاش برای دقت هستیم، لطفاً توجه داشته باشید که ترجمه‌های خودکار ممکن است حاوی خطاها یا نواقصی باشند. سند اصلی به زبان بومی خود باید به عنوان منبع معتبر در نظر گرفته شود. برای اطلاعات حیاتی، ترجمه حرفه‌ای انسانی توصیه می‌شود. ما مسئول هیچ گونه سوءتفاهم یا تفسیر نادرستی که از استفاده این ترجمه ناشی شود، نیستیم.