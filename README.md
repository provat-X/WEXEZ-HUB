<div align="center">

<img src="app/src/main/res/drawable-nodpi/wexe_logo.webp" alt="WEXE HUB" width="220">

# WEXE HUB
**Your music. Your world.**

A personalized Android music player with a clean library, playlists, synchronized lyrics, a landscape split-player experience, and a custom WEXE HUB identity.

</div>

---

## Current project focus

- WEXE HUB branding across the launcher, splash screen, and user-facing strings.
- Landscape player with album artwork on the left and lyrics on the right.
- Soft blue ambient glow and blurred artwork background.
- Manual lyrics entry and editing through the existing lyrics editor.
- Smooth playback controls and responsive portrait/landscape layouts.

## Build

The repository includes GitHub Actions workflows for Android linting and APK builds. To build locally:

```bash
chmod +x gradlew
./gradlew --no-daemon assembleGithubDebug
```

The build must complete successfully and the resulting APK should be tested on an Android device before a release is considered ready.

## License and attribution

This project is based on an existing open-source Android music player. Required upstream copyright, license, and attribution notices are retained in the repository's license notice and source files. Please review those notices before redistributing builds.

