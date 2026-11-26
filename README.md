# StreamLink Engine v1.0.0-stable

Low-latency PC-to-Android game streaming suite built from scratch in **Rust** (DXGI + NVENC/x264 + WASAPI/Opus + ViGEmBus) and **Native Kotlin / Jetpack Compose** (MediaCodec SurfaceView + Cauchy RS FEC + Multi-Touch Controller).

- **Official Download Portal:** https://stream.7ust.store


## Included Release Files
- `StreamLink-Host.exe` (7.27 MB, Windows 10/11 x64) — `SHA-256: 10e7cb9da9e3c8b148fd1d22cdf10c776000b2b74a224c126bdbcc44d5670d74`
- `StreamLink-Android.apk` (11.38 MB, Android arm64-v8a/universal) — `SHA-256: 85985baf065a5b6f04f28d8f53d7ad3a4f5801049cae50d5e06f3bbaa6fb3065`
- `StreamLink-Source-v1.0.0.zip` — Complete source archive (`pc-host/` + `android-client/`)

## Ports & Quick Start
- UDP `47990`: LAN mDNS / Broadcast discovery
- UDP `47991`: Video/FEC, Opus audio, 50ms telemetry, and Gamepad/Mouse/Keyboard input
