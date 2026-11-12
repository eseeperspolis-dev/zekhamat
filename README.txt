محاسبه وزن و ضخامت — نسخه PWA (کار بدون اینترنت)
==========================================================

فایل‌ها (هر شش فایل باید کنار هم، در ریشه ریپو باشند):
  index.html
  sw.js
  manifest.webmanifest
  icon-192.png
  icon-512.png
  apple-touch-icon.png

به‌روزرسانی در GitHub:
  1) زیپ را Extract All کنید.
  2) در صفحه ریپو: Add file > Upload files. هر شش فایل را بکشید و Commit کنید.
     فایل‌های هم‌نام قبلی جایگزین می‌شوند.
  3) چند دقیقه صبر کنید تا GitHub Pages به‌روز شود.
  4) یک‌بار با اینترنت صفحه را باز کنید. بعد از آن بدون اینترنت هم کار می‌کند.

ویندوز:
  - دابل‌کلیک روی index.html در Edge یا Chrome اپ را باز می‌کند و بدون اینترنت هم کار می‌کند.
    (در این حالت فقط گزینه نصب PWA فعال نیست.)
  - برای نصب: آدرس HTTPS اپ را در Edge یا Chrome باز کنید و Install را بزنید.
iPhone: Safari > Share > Add to Home Screen.
Android: Chrome > Install app.

نکات:
  - کار بدون اینترنت (سرویس‌ورکر) فقط روی HTTPS مثل GitHub Pages یا localhost ثبت می‌شود.
  - برای نسخه بعدی، در sw.js مقدار CACHE_VERSION را عوض کنید (مثلاً wt-calc-v3).
  - نسخه فعلی کش: wt-calc-v2
