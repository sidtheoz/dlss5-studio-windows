# DLSS5 Studio — Windows Edition

Made for Windows by **Sid M**. A community desktop interface based on [Merserk’s DLSS 5 Visual Enhancer v7.0](https://github.com/Merserk/dlss5-visual-enhancer/tree/v7.0).

## Download

Get **DLSS5-Studio-Windows-1.0.zip** from [Releases](https://github.com/sidtheoz/dlss5-studio-windows/releases), or visit the [free Gumroad listing](https://sidmtools.gumroad.com/l/dlss5-studio). Use the Windows ZIP under Assets, not GitHub’s automatically generated Source code archives.

1. Extract the entire ZIP into a writable folder.
2. Open **DLSS5 Studio.exe**. Keep all bundled folders beside it.
3. Wait for the local engine to load, then select a workspace.

## Features

- Neural rendering for images and video.
- RTX Video Super Resolution and SDR-to-HDR video controls.
- Before/after image swipe comparison with fullscreen and batch selection.
- DLSS frame interpolation, live playback, output library and presets.
- Dedicated Windows window; no separate Python installation or Chrome window.

## Compatibility

Windows 10/11 x64, .NET Framework 4.8, [WebView2 Evergreen Runtime](https://developer.microsoft.com/microsoft-edge/webview2/), and a compatible NVIDIA RTX GPU/driver.

**Frame interpolation requires RTX 40/50-series DLSS Frame Generation support. RTX 20/30 cards, including RTX 3060 Ti, cannot use it. Auto and Cascade have the same requirement.** Neural rendering and upscaling have separate requirements. This desktop build was tested on RTX 4090.

## Attribution

Inspired by Merserk's repo, compiled and built for Windows by Sid M. The v7.0 MIT copyright and bundled third-party license notices are retained in the download. Third-party components retain their own licenses. DLSS and RTX are NVIDIA technologies; this is not an official NVIDIA application.

The release ZIP excludes personal outputs, render logs and saved application preferences. A SHA-256 checksum is provided with each release.
