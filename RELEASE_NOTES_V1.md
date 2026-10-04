# Youtube Studio · V1 — Official Build

V1 includes the latest approved interface, download, conversion, Library, playback and recovery improvements.

- Clearer channel cards with supported public banners, overlapping profile pictures, subscriber information and accessible expanded details.
- A collection download toolbar aligned to the content area, with wrapping controls and space reserved below the final cards.
- Improved Quality selection, Settings layout, collection List view and brief notifications.
- Public preview fixes and simpler refresh/fullscreen controls.
- Video output choices including MP4, MOV, MKV and WebM; audio choices including MP3, M4A, WAV, FLAC and OGG. Conversion keeps the original media.
- Bounded history rendering, direct Library lookup, reliable playback persistence, duplicate inspection and recovery improvements.
- About now shows **V1** / **Official Build** with Thanun's social links.
- A refreshed branded English installer with directory choice, shortcuts and data-preserving uninstall.

## Downloads

Choose **Setup** for normal installation or **Portable** to run without installation. Both are Windows x64 builds, version **1.0.0**. Close the running app before replacing an older build. Saved media is not deleted by installation or uninstall.

The Windows executables are **unsigned**. Windows may display an unknown-publisher notice. `SHA256SUMS.txt` identifies the exact release files. Installed builds verify signed update metadata and installer hashes before offering the verified installer; portable updates use manual replacement.

## Verification and limits

Build, 214 unit tests, focused source/package desktop regressions, portable startup and isolated install/launch/uninstall checks passed. The latest channel-card/toolbar checks pass in the V1 package. A local signed HTTPS fixture verifies update trust, download and restart integrity; V1 establishes the production feed baseline, so an actual two-version production update has not yet been exercised.

Native installer welcome text and installation behavior were verified. Installer artwork was inspected separately; hidden-window capture could not verify the painted wizard. Physical DPI, assistive-technology and disk-full/power-loss testing remain unverified.

The Runtime Source Information archive supplies the pinned FFmpeg source, upstream build scripts, configuration/licenses and dependency-revision inventory. Complete linked/transitive dependency source assembly and reproducibility review remain incomplete; this archive is not a complete reviewed corresponding-source package or certification.

Public source availability, formats and captions can change. The app uses public content only and does not request login or cookies.
