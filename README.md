# Relic Client Downloads

Phone and desktop client installers for Relic, the e-ink voice recorder.

**[Go to the download page](https://github.com/ltsqyg-lab/relic-downloads/releases/latest)**

| Platform | File | Notes |
|---|---|---|
| Android | `Relic_android.apk` | Install directly; allow "unknown sources" once |
| iPhone / iPad | `Relic_ios_unsigned.ipa` | **Unsigned**; sign it with your own Apple ID using Sideloadly / AltStore |
| macOS | `Relic_mac.dmg` | Apple silicon. If macOS says the app "is damaged", run `xattr -dr com.apple.quarantine /Applications/Relic.app` |
| Windows | `Relic_windows_setup.exe` | 64-bit. Not code-signed; in SmartScreen, click "More info → Run anyway" |
| Windows | `Relic_windows.msi` | For bulk deployment |

The installers contain no account credentials; they only connect to the server after you sign in.

This repository only hosts installers; it contains no source code.
