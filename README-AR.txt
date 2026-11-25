حزمة النشر المحسّنة لمتجر Technova

هذه الحزمة تضم:
- index.html: صفحة المتجر الأصلية مع ربط PWA.
- manifest.webmanifest: الاسم العربي/الإنجليزي، اتجاه RTL، شاشة مستقلة وأيقونات.
- service-worker.js: تخزين أساسي ودعم فتح المتجر عند انقطاع الاتصال.
- _headers: أنواع المحتوى وسياسات التخزين المناسبة على Netlify.
- icons: أيقونات 192 و512.

طريقة تحديث موقع Netlify:
1) فك ضغط Technova-Netlify-Final.zip.
2) افتح لوحة Netlify للموقع technova-store72.
3) ادخل إلى Deploys ثم اسحب محتويات المجلد المفكوكة إلى منطقة الرفع اليدوي (Manual deploy).
   يجب أن تكون index.html وmanifest.webmanifest وservice-worker.js و_headers في جذر النشر، لا داخل مجلد فرعي.
4) بعد اكتمال النشر، اختبر:
   https://technova-store72.netlify.app/
   https://technova-store72.netlify.app/manifest.webmanifest
   https://technova-store72.netlify.app/service-worker.js
5) افتح https://www.pwabuilder.com والصق رابط الموقع ثم افحصه واختر Android لإنشاء حزمة.

تنبيه:
لا يمكن تعديل موقع Netlify المنشور مباشرة من رابط عام فقط؛ يتطلب ذلك صلاحية إلى حساب Netlify أو أن تنفذ رفع هذا المجلد من لوحة الموقع. لم يتم إنشاء APK داخل هذه الحزمة.
