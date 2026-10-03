# Bible Study Group Android App

This repository contains the Bible Study Group Android app.

Features:
- English, Afaan Oromoo and Amharic UI/Bible reading
- Responsive phone/tablet layout
- Bible chapters can be cached on the device after first online reading
- Android WebView app with the website bundled inside the APK
- GitHub Actions automatically builds an installable debug APK

## Build the APK from a phone

1. Create a GitHub repository named `BibleStudyGroup`.
2. Upload the contents of this repository (upload the files/folders, not this ZIP itself).
3. Make sure `.github/workflows/build-apk.yml` is present.
4. Push/save the files to the `main` branch.
5. Open the repository's **Actions** tab.
6. Select **Build Bible Study APK**.
7. Tap **Run workflow** if it has not already run.
8. Open the completed workflow run.
9. Scroll to **Artifacts**.
10. Download `BibleStudyGroup-debug-apk`.
11. Extract the downloaded ZIP and install `app-debug.apk` on your Android phone.

## Important

The debug APK is intended for testing/personal installation. A signed release APK should be created later if you want to distribute the app publicly or publish it on Google Play.

The Android build uses Gradle and the Android Gradle Plugin.
