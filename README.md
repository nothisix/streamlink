# StreamLink Engine v1.0.0-stable

Low-latency PC-to-Android game streaming suite built from scratch in **Rust** (DXGI + NVENC/x264 + WASAPI/Opus + ViGEmBus) and **Native Kotlin / Jetpack Compose** (MediaCodec SurfaceView + Cauchy RS FEC + Multi-Touch Controller).

## Included Release Files
- `StreamLink-Host.exe` (7.25 MB, Windows 10/11 x64) — `SHA-256: 1ced1e254bff27c0af65692ddfb9e50ebb355aaa45fa0915a1e0e3ad17d031c9`
- `StreamLink-Android.apk` (10.93 MB, Android arm64-v8a/universal) — `SHA-256: 2aba52a92c3b37ff04dc33bf5ecb6a65106f68ff25fff81f831baf2ea6c37ba7`
- `StreamLink-Source-v1.0.0.zip` — Complete source archive (`pc-host/` + `android-client/`)

## Ports & Quick Start
- UDP `47990`: LAN mDNS / Broadcast discovery
- UDP `47991`: Video/FEC, Opus audio, 50ms telemetry, and Gamepad/Mouse/Keyboard input
