# Youtube Studio 1.1.0

- Batch downloads now prepare in the background while you keep browsing. Ready items begin downloading as the rest are checked.
- Downloads shows preparation, item results, retry and cancellation controls.
- A clean, collapsible card at the bottom right shows real download and requested-output progress across other pages.
- Library search uses a subtle themed focus cue instead of the blue border.
- Settings adds Clear all history with confirmation. Library, files and unfinished tasks are preserved.
- App controls and scrollbars follow the theme, including the video preview description.

## Downloads

Choose Setup for installation or Portable to run without installation. Existing installed builds can detect this update through the signed stable feed; applying it requires opening the verified installer. Replace portable builds manually.

SHA256SUMS.txt, third-party notices and the unchanged Runtime Source Information accompany the Windows x64 downloads. Windows executables remain unsigned, consistent with the previous release.

## Verification

250 automated tests, all ten packaged regression suites, seven new background-workflow desktop checks, package/runtime hash checks and signed-update trust/integrity tests passed. All tests used disposable profiles.

Live large-channel timing, physical DPI/monitor behavior and a new native installation/upgrade were not tested in this release. Provider-owned YouTube controls remain separate from app styling. The existing runtime source/reproducibility limitations remain unchanged.
