NETX SPEED TEST — Android APK project

Included:
- www/index.html: neon gaming-style speed test interface
- package.json: Capacitor dependencies
- capacitor.config.json: app identity
- .github/workflows/build-apk.yml: cloud build workflow

BUILD USING ONLY YOUR PHONE (GitHub Actions):
1. Download and extract this ZIP on your phone.
2. Sign in or create a GitHub account in Chrome.
3. Create a new PUBLIC or PRIVATE repository named netx-speed-test.
4. Upload the extracted project files and folders to the repository root. Ensure .github/workflows/build-apk.yml is included. If the GitHub mobile upload screen hides dot-folders, use GitHub in Chrome with Desktop site enabled.
5. Open the repository's Actions tab and select "Build NETX Android APK".
6. Tap "Run workflow" if it hasn't started automatically. Wait until the run succeeds.
7. Open the completed workflow run, scroll to Artifacts, and download NETX-Speed-Test-debug-APK.
8. Extract the downloaded artifact ZIP. It contains app-debug.apk.
9. Tap app-debug.apk to install. Android may ask you to allow installs from your browser or file manager; only enable this for the app you are using to install your own APK, then turn it off again.

Notes:
- A debug APK is for personal testing. Do not publish it as a trusted release without reviewing and signing a release build.
- Internet speed results rely on Cloudflare's public test endpoints; upload may fail on some networks/browsers.
- The app measures a test transfer, not the live speed of every app or background network process.
- GitHub account and internet access are required for this phone-only cloud build path.
