# Isai Malai

A Tamil-only audio player with a green mobile now-playing screen, search, a queue, saved tracks, and lossless-format local playback.

- Website: https://isai-malai.vercel.app/
- Updated source bundle, including the Android WebView wrapper: [Isai-Malai-source.zip](https://github.com/Vasanthank994499/isai-malai/blob/main/Isai-Malai-source.zip)
- Project license: [GNU GPL version 3](https://github.com/Vasanthank994499/isai-malai/blob/main/LICENSE)

## Audio catalog

The site searches Tamil-tagged Internet Archive records. It checks the item file list for a browser-playable FLAC, WAV, AIFF, or explicitly identified ALAC source before enabling playback; it never falls back to lossy files. Archive.org is not a complete Tamil music catalog, search matches may be non-song audio, and uploader-provided rights and format details are not independently verified. A lossless file format does not prove that the original master was lossless. This app does not include or license commercial recordings.

## Android

The source bundle includes an Android WebView project. The workflow under **Actions → Build Isai Malai Android APK** can produce an unsigned debug APK artifact after the Android SDK license input is checked. The artifact is temporary and is not a Google Play release. Chrome on Android can also install the website as a PWA.

## BitChord reference

The mobile player layout was informed by the supplied BitChord APK. BitChord's upstream project is licensed under GPL-3.0: [upstream license](https://github.com/kushagrasinghx/BitChord/blob/main/LICENSE). Isai Malai contains original source and branding; it does not include BitChord code, logo, or recordings. GPL-3.0 for the app software does not grant rights to music, cover art, or compositions.
