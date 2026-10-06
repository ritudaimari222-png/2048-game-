# Build the 2048 APK from your phone

1. Create/sign in to a GitHub account.
2. Create a new repository, for example: `2048-game`.
3. Upload ALL files and folders from this project into the repository.
   Important: upload `.github/workflows/build-apk.yml` too.
4. Open the repository's **Actions** tab.
5. Select **Build 2048 APK**.
6. Tap **Run workflow** (or push to the main branch).
7. Wait for the workflow to finish.
8. Open the completed workflow run and download the artifact named **2048-debug-apk**.
9. Extract the downloaded artifact. The `.apk` inside is the installable debug APK.

If GitHub asks for permission to run workflows, allow it for your repository.

This produces a debug APK for personal testing. A Play Store release needs a signed release build and app signing.
