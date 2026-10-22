# NEXORA TOOLS

واجهة أدوات عملية للمبرمجين، مبنية بـ HTML وCSS وJavaScript بدون أي مكتبات أو خطوات بناء.

## الأدوات الحالية
- JSON Formatter / Minifier
- Password Generator (Web Crypto API)
- Text Transformer
- Color Lab (HEX / RGB / HSL)
- Base64 Encoder / Decoder مع UTF-8
- Unix Timestamp Converter

## التشغيل
افتح `index.html` في متصفح حديث. لا تحتاج لتثبيت برامج.

## النشر المجاني عبر GitHub Pages
1. أنشئ مستودعًا عامًا (Public) على GitHub.
2. ارفع `index.html` و`favicon.svg` و`README.md` إلى جذر المستودع.
3. افتح Settings → Pages.
4. اختر Deploy from a branch، ثم `main` و`/(root)`، واضغط Save.
5. انتظر انتهاء عملية `pages build and deployment`، ثم افتح الرابط الذي تعرضه صفحة Pages.

## حدود النسخة
- الأدوات تعمل محليًا داخل المتصفح ولا ترسل النصوص إلى Backend.
- لا توجد حسابات أو مزامنة أو قاعدة بيانات في هذه النسخة.
- لتطوير Backend لاحقًا: Supabase (Auth + PostgreSQL) مع API serverless على Vercel، بعد تحديد الميزات التي تحتاج تخزينًا فعليًا.
- استخدم HTTPS ولا تُدخل أسرارًا حساسة في أدوات لا تثق بها.
