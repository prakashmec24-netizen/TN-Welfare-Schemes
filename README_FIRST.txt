TN WELFARE CONNECT - ANDROID STUDIO SOURCE

This project wraps the existing TN Welfare Connect HTML app in an Android WebView.

OPEN AND RUN:
1. Install Android Studio: https://developer.android.com/studio
2. Extract this ZIP to a normal folder.
3. Open Android Studio > Open, then select the extracted TNWelfareConnect_Android folder.
4. Allow Gradle sync. Install Android SDK 35 if Android Studio asks.
5. To test on your phone: enable Developer options and USB debugging, connect by USB,
   select your phone in Android Studio, and press Run (green triangle).

BUILD AN APK:
1. In Android Studio choose Build > Build Bundle(s) / APK(s) > Build APK(s).
2. When complete, click Locate. The APK is normally at:
   app/build/outputs/apk/debug/app-debug.apk
3. Transfer the APK to your Android phone and install it. You may need to allow your
   file manager to install unknown apps.

NOTES:
- This ZIP is source code, not a prebuilt APK.
- The app's HTML and JavaScript are in app/src/main/assets/index.html.
- External HTTPS links (such as government portals) open in the phone browser.
- Features requiring a hosted backend will work only after that backend is deployed
  and the HTML is configured to use its URL.
- Login in the supplied HTML is prototype/demo login, not production-secure authentication.
