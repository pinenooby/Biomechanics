# Biomechanics: Android app

The whole game is `app/src/main/assets/index.html`, shown full-screen in an Android WebView. It works offline and saves in the app.
To update the game later, replace that file and rebuild.

## Easiest: build the APK online (no installs)
1. Make a free account at github.com and create a new repository.
2. Upload every file and folder from this zip into it (drag them in; keep the `.github` folder).
3. Open the repo's **Actions** tab, then **Build APK**, and wait about 3 minutes for the green check.
4. Open the finished run and download the **Biomechanics-apk** artifact (a zip containing `app-debug.apk`).
5. Copy the APK to your phone and open it. Allow "Install unknown apps" for your file manager or browser when asked.

## Or with Android Studio
Open this folder, wait for Gradle sync, then **Build > Build APK(s)**. The file is `app/build/outputs/apk/debug/app-debug.apk`.
