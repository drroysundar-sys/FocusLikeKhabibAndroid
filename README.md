# Focus Like Khabib — Android project

This is an Android Studio project wrapper for the local Focus Like Khabib Pomodoro app.

## Build an APK
1. Install Android Studio on a computer.
2. Extract this project ZIP.
3. In Android Studio, choose **Open** and select the `FocusLikeKhabibAndroid` folder.
4. Let Gradle sync and install any requested Android SDK (API 35).
5. Choose **Build → Build APK(s)**.
6. The debug APK is normally created at `app/build/outputs/apk/debug/app-debug.apk`.

The source project has not been compiled or device-tested in this environment. This ZIP is an Android Studio project, not an APK.

## Build automatically in GitHub (no Android Studio needed on your phone)
1. Create a repository on GitHub and upload the contents of this project folder.
2. Open the repository's **Actions** tab.
3. Select **Build Focus Like Khabib APK** and tap **Run workflow** (or push to `main`).
4. When the workflow finishes successfully, open that run and download the `FocusLikeKhabib-debug-apk` artifact.
5. Extract the downloaded artifact and install `app-debug.apk` on your Android phone. Android may ask you to allow installation from that source.

The GitHub workflow is included to compile the APK in a clean Android build environment. This environment does not have Android SDK/Gradle installed, so the APK has not been compiled or tested here.
