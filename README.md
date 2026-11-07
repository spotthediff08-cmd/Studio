# Animation Studio — fresh Android project

Android Studio / GitHub Actions project using Kotlin + Jetpack Compose.

## Build APK with GitHub
1. Create a new GitHub repository.
2. Upload the contents of this ZIP (not the containing folder).
3. Open Actions and run **Android Debug APK** (or push to `main`).
4. Download the `AnimationStudio-debug` artifact after the workflow succeeds.

## Current included foundation
- Dark-themed Compose app with Home, Scenes, Subtitles and Export tabs.
- Multi-image picker and thumbnail scene list.
- Audio file picker.
- SRT file picker placeholder and editable subtitle text area.
- Global camera-motion selection UI.
- Output resolution selection UI.
- GitHub Actions APK build workflow.

## Important status
This is a clean, buildable starter/foundation, not yet the finished video editor.
MP4 rendering, SRT parsing and burn-in, 3x3 contact-sheet splitting, project save/load,
scene duration controls, transitions, preview and FFmpeg encoding are not implemented yet.
The Export page explicitly indicates this. Add and test these features in stages before
using it to produce final videos.
