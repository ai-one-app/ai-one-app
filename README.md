# AI-ONE
واجهة عربية RTL قابلة للتثبيت كتطبيق PWA ومتصلة بمشروع Supabase مستقل.
## النشر
فعّل GitHub Pages من Settings → Pages واختر الفرع main ومجلد الجذر. افتح رابط Pages في Safari على iPhone ثم Share → Add to Home Screen.
## الوظائف
- Supabase Auth بالبريد وكلمة المرور.
- حفظ المحادثات والرسائل وفق سياسات RLS.
- استدعاء Edge Function ai-router باستخدام جلسة المستخدم.
- يستخدم العميل مفتاح Supabase Publishable فقط؛ لا توجد مفاتيح مزودي AI في المتصفح.
## ملاحظات
قد يتطلب التسجيل تأكيد البريد الإلكتروني. يجب ضبط مفاتيح مزودي AI داخل Edge Function Secrets. النسخة الحالية تدعم النص فقط؛ الصور والصوت والملفات مرحلة لاحقة.