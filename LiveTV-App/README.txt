BUILD THE APK (free, no Android Studio needed)
1. Create a free account at github.com and make a new repository (e.g. livetv-app).
2. Upload ALL files/folders of this project (www, assets, .github, package.json, capacitor.config.json).
3. Open the repo > Actions tab > "Build APK" > Run workflow.
4. After ~5 minutes open the finished run > Artifacts > download LiveTV-apk > unzip > app-debug.apk.
5. Copy the APK to any Android phone, tap it, allow "Install unknown apps".

To change the splash text/photo: edit www/index.html (id="splash") and replace assets/icon-only.png.
