# ?? MusicFlow — Web & iOS Application

> **Ultra-premium lossless music streaming player for Web & iOS.**
> Zero ads, 320kbps Lossless Audio, Live Synced Lyrics, Reactive Audio Visualizers, and 10-Band EQ.

---

## ? Features
- ?? **320kbps Lossless Audio Streaming** — High-fidelity audio playback with zero stutter.
- ?? **Reactive Audio Visualizers** — Real-time Web Audio API frequency analysis and dynamic waveform canvas.
- ??? **10-Band Graphic Equalizer** — Bass Boost, 3D Spatial Audio, and genre-tailored EQ presets.
- ?? **Live Synced Lyrics** — Time-coded scrolling lyrics powered by LRCLIB.
- ?? **iOS Native & PWA Ready** — Background audio playback, lockscreen controls, and sideloadable .ipa.
- ? **Offline Mode** — Client-side caching and offline listening support.

---

## ?? iOS Build (Automated via GitHub Actions)
Every push to main automatically runs **macos-14 Xcode CI** to compile the native Mach-O binary and generate a signed-ready **MusicFlow.ipa** available under **Actions ? Artifacts**.

### Sideloading Instructions:
1. Download **MusicFlow-iOS-IPA.zip** from the latest GitHub Actions run and extract MusicFlow.ipa.
2. Open **AltStore**, **SideStore**, or **Sideloadly** on your device or computer.
3. Import MusicFlow.ipa, enter your Apple ID credentials to sign, and enjoy!
