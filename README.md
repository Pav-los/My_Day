# My Day: build the Android APK (no Android Studio needed)

1. Create a free account at github.com and make a new private repository (name: my-day).
2. Upload ALL files from this folder to it, including the hidden .github folder
   (easiest: on your computer, install GitHub Desktop, or use "uploading an existing file" on the repo page and drag the whole folder contents).
3. Open the repository, tap/click the "Actions" tab, choose "Build APK", and wait 3-5 minutes until it shows a green check.
4. Open the finished run, scroll to "Artifacts", download "my-day-apk" (a zip), and unzip it to get app-debug.apk.
5. Send app-debug.apk to your phone (Google Drive, email, USB). Open it and allow "Install unknown apps" for that app when Android asks.

Notes:
- The app works fully offline. Data is stored inside the app.
- It has its own storage, separate from the browser version. To move your data: in the browser version go to History > Export, copy the text, then in the app go to History > Backup > paste > Import.
- This is a debug build for personal use. It uses the default Capacitor icon.
