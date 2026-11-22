# الادخار

تطبيق ويب (PWA) لتتبع الادخار والسلفات. يشتغل بدون إنترنت بعد أول فتح.

## النشر على GitHub Pages
1. أنشئ مستودعا جديدا على GitHub (مثلا `epargne`).
2. ارفع كل محتويات هذا المجلد (index.html, sw.js, manifest.webmanifest, مجلد icons).
3. Settings ← Pages ← Source: Deploy from a branch ← Branch: main و Folder: /(root) ← Save.
4. بعد دقيقة يصبح الرابط: https://USERNAME.github.io/epargne/
5. افتح الرابط في الهاتف: Chrome ← ⋮ ← "تثبيت التطبيق" (Android) / Safari ← مشاركة ← "إضافة إلى الشاشة الرئيسية" (iPhone).

## ملاحظات
- البيانات تُحفظ داخل متصفح الجهاز فقط، لا تُرفع إلى GitHub.
- لنقل بياناتك من النسخة القديمة: نزّل نسخة احتياطية منها، ثم استرجعها من الملف في التطبيق الجديد.
- عند تعديل الملفات، غيّر رقم `V` في sw.js (مثل epargne-v2) لتصل التحديثات للجهاز.

