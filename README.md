# Spider AI Builder — Android starter
This is a WebView Android wrapper for the existing offline HTML prototype. It is **not** connected to an AI model, and it cannot yet build other APKs. The HTML download button may not work inside WebView; it works in Chrome.

## Build using only an Android phone + GitHub
1. Create a new empty GitHub repository (public or private).
2. Upload the **contents** of this ZIP to the repository root (keep `.github/workflows/build-apk.yml`). GitHub mobile browser may make uploading directories difficult; use a Git client or desktop-site mode, or upload files individually preserving paths.
3. Open **Actions → Build Android APK → Run workflow** (or push to main).
4. When build succeeds, open its run → **Artifacts → SpiderAIBuilder-debug-apk**, download ZIP, extract `app-debug.apk` and install it.

Requires internet and GitHub Actions access. APK is a debug build, not a Play Store release. Unknown-app install permission may be required. Do not enter private API keys into the HTML.
