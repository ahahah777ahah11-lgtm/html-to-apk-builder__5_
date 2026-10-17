# دليل بناء ملف APK (HTML to APK Builder)

حزمة مشروع أندرويد متكاملة ومجهزة لتحويل تطبيق الويب إلى تطبيق أندرويد حقيقي APK بصيغة جاهزة للتثبيت على الهواتف.

## تفاصيل التطبيق:
- اسم التطبيق: Smart Debt Messenger
- معرف الحزمة: com.smartdebt.app
- الإصدار: 1.0.0

### طرق بناء ملف الـ APK:
1. **Klencod IDE على الهاتف**: افتح التطبيق -> Open Project -> Build APK.
2. **GitHub Actions سحابياً**: ارفع المجلد لمستودع جيت هب -> Actions -> تحميل ملف الـ APK جاهزاً.
3. **Android Studio**: فتح المشروع -> Build -> Build APK(s).
4. **سطر الأوامر**: تشغيل `./build.sh` أو `gradlew assembleDebug`.
