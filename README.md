# TubeStitch Android APK Project

Stitches your selected images, voiceover audio (`.mp3`/`.wav`/`.m4a`), and duration text file (`timeline.txt`) into a 1080p YouTube `.mp4` video using native Android FFmpeg, then saves it to `Movies/TubeStitch` in your phone Gallery.

## Option A: Build the APK in Android Studio (PC / Mac / Linux)
1. Unzip `TubeStitch_Android_Project.zip`.
2. Open **Android Studio** -> **Open** -> select the unzipped `TubeStitch` folder.
3. Wait for Gradle Sync to finish, then click **Build -> Build Bundle(s) / APK(s) -> Build APK(s)**.
4. Your installable APK will be at `app/build/outputs/apk/debug/app-debug.apk`.

## Option B: Build the APK in the Cloud on GitHub (No PC or Android Studio Needed)
1. Create a free repository on GitHub and upload the contents of this `TubeStitch` folder (including the `.github/workflows/build-apk.yml` file).
2. Click the **Actions** tab in your GitHub repository.
3. Click the **Build TubeStitch APK** workflow run and download **`TubeStitch-debug-apk`** from the **Artifacts** section at the bottom of the page.
