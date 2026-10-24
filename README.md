# SMART MART BD Android Starter

This is a starter Android project, not a finished store-management application. It currently contains a basic UI shell. POS transactions, stock/purchase accounting, customer dues, reports, offline database persistence, and backup/restore still need implementation before business use.

## Build APK using GitHub Actions from a phone
1. Create a GitHub repository.
2. Upload the *contents of this project folder* to the repository root (so `settings.gradle.kts` is at the root).
3. Open the Actions tab and enable Actions if prompted.
4. Select **Build SMART MART BD APK** and press **Run workflow**.
5. When the run finishes successfully, open the run, scroll to Artifacts, and download `SMART-MART-BD-debug-apk`. Extract the ZIP to get `app-debug.apk`.

The workflow builds a debug APK for testing. It is not a signed release APK for Play Store distribution.
