# Isai Malai

Isai Malai is a Tamil-focused music player demo with a responsive website, installable PWA shell, and Android WebView wrapper. It uses original Isai Malai branding and common music-player interactions.

## Playback today

The player can play audio files selected from the listener’s own device. Those files stay on the device; the app does not upload them. The project does not include or stream commercial recordings.

## Tamil catalog and music rights

No label, distributor, or streaming-catalog license is connected yet. To offer a searchable, playable commercial Tamil catalog online, the app needs a provider agreement and authorized catalog/playback API. This repository does not claim to contain all Tamil songs or Spotify’s catalog.

## Website deployment

The GitHub Pages workflow extracts `dist/` from `Isai-Malai-source.zip` and deploys it on pushes to `main`. Pages must be enabled for this repository and supported by the account plan.

## Android APK

The Android workflow can produce an unsigned debug APK as a GitHub Actions artifact. It is manual and gated by an explicit input to accept the Android SDK license agreements. A debug APK is not a signed Play Store release.

## Project license

No open-source license is attached to this project. The project code and its assets are not a grant of rights to any third-party music recordings.
