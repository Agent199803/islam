# رفيق العبادة — Islamic Tracker

تطبيق Android عربي لمتابعة العبادات اليومية، الأذكار، المسبحة والإحصائيات.

## التقنية
- Flutter / Dart
- Material 3
- تخزين محلي SharedPreferences
- fl_chart للإحصائيات
- GitHub Actions لبناء APK و AAB

## البناء محلياً
```bash
flutter pub get
flutter analyze
flutter test
flutter build apk --release
flutter build appbundle --release
```

## GitHub
ارفع المشروع إلى مستودع GitHub ثم ادفع إلى `main`.
سيتم تشغيل GitHub Actions وبناء APK وAAB تلقائياً.

## ملاحظات
هذه النسخة الأساسية هي أساس النسخة النهائية الموسعة. لا تحتوي حالياً على مواقيت الصلاة أو قاعدة نص القرآن أو خدمة تحديد القبلة، حتى يتم إدخال مصادر موثوقة واختبارها بشكل مستقل.
