# Dwallet Android App
Tabs after login: Wallet | P2P | Profile. Login/Register show full screen (no tabs).

1. Edit `app/build.gradle.kts`: set BASE_URL (https) and, if needed, PATH_WALLET / PATH_P2P / PATH_PROFILE
   (run `php artisan route:list` on your server to confirm the real URLs).
2. Build: Android Studio > Open folder > Build > Build APK(s)
   OR upload this folder to a GitHub repo > Actions > "Build APK" > Run workflow > download artifact `dwallet-apk`.
3. Copy the .apk to the phone, allow "install unknown apps", install.
