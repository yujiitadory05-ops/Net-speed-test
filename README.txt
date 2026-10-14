NET SPEED TEST — Android APK project

Files:
- www/index.html — neon gaming-style NET app
- package.json — Capacitor dependencies
- capacitor.config.json — Android app identity
- .github/workflows/build-apk.yml — automated APK build

Phone-only build:
1. Extract this ZIP on your phone.
2. Open your GitHub repository in Chrome.
3. Upload the CONTENTS of this folder into the repository root. Keep the .github/workflows/build-apk.yml folder structure.
4. Commit the changes to the main branch.
5. Open the repository Actions tab. Choose "Build NET Android APK" and tap Run workflow, or wait for the push-triggered build.
6. When the run succeeds, open it and download the "NET-Speed-Test-APK" artifact.
7. Extract the artifact ZIP and tap app-debug.apk to install it.

App name: NET Speed Test
Package ID: com.net.speedtest
This is a debug APK for personal testing. Speed test endpoints are public and upload testing may fail on some networks.
