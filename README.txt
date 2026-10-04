MakeMyTrip WebView APK sample

URL:
https://www.makemytrip.com/

Build:
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Build > Build App Bundle(s) / APK(s) > Build APK(s).
4. The APK will be under app/build/outputs/apk/debug/.

For your own website, change the URL in MainActivity.java:
webView.loadUrl("https://your-site.com/");
