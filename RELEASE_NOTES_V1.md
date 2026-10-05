# Youtube Studio · V1 — Official Build

This refreshed official Windows x64 release is version **1.0.0** and includes the automatic-update popup and all existing download, Library, playback, conversion and background-work features.

## What's new

- A compact update popup consistent with Settings, with verified release metadata, version/channel/size/date details and real release notes when supplied.
- Live update download percentage, downloaded bytes, measured speed and estimated remaining time.
- Closing and reopening the popup preserves the active download. Settings stays synchronized with the same updater.
- Explicit update cancellation and retry, guarded installer opening, and a clear ready-to-install state.
- Keyboard focus management, responsive scrolling, reduced-motion support and automatic update offers that wait until playback fullscreen exits.
- Background batch preparation and floating download progress remain available. History clearing preserves Library files and unfinished work.

## Downloads and replacement

Choose **Setup** for normal installation or **Portable** to run without installation. Both files are Windows x64, version **1.0.0**. This release replaces the earlier GitHub V1 and 1.1.0 releases.

If you already have an earlier **1.0.0** or **1.1.0** build, close the app and install this replacement manually. The updater intentionally offers only numerically newer versions, so it will not automatically replace the same version or downgrade 1.1.0. Saved media and application data are preserved by the installer.

For future updates, installed builds check the existing signed stable feed. **Verified** refers to the release metadata signature; installer bytes are separately checked against SHA-256 before readiness and before opening. Applying an update retains the Windows installer confirmation: the app closes, you complete installation in Windows, then launch the app again. Portable builds use manual replacement.

## Verification and limits

The full 254-test unit suite, renderer build and pinned-runtime integrity checks pass. The fresh package passes update-popup interaction tests and version identity checks. SHA-256 checksums accompany all release downloads.

Windows executables remain unsigned. Public source availability, formats and captions can change. The app supports public content only and does not request login or cookies. Physical DPI, assistive-technology and a real native downgrade/upgrade remain unverified for this replacement. No installation was performed on the owner's data during release testing.

The Runtime Source Information archive is unchanged: it provides the pinned FFmpeg source, build scripts, configuration/licenses and dependency-revision inventory. Complete linked/transitive dependency source assembly and reproducibility review remain incomplete.
