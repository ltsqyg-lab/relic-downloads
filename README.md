# Relic 客户端下载

墨水屏录音笔 Relic 的手机与电脑客户端安装包。

**[前往下载页](https://github.com/ltsqyg-lab/relic-downloads/releases/latest)**

| 平台 | 文件 | 说明 |
|---|---|---|
| Android | `Relic_android.apk` | 直接安装，允许一次「未知来源」 |
| iPhone / iPad | `Relic_ios_unsigned.ipa` | **未签名**，需用 Sideloadly / AltStore 以自己的 Apple ID 签名 |
| macOS | `Relic_mac.dmg` | Apple 芯片。提示「已损坏」时执行 `xattr -dr com.apple.quarantine /Applications/Relic.app` |
| Windows | `Relic_windows_setup.exe` | 64 位。无代码签名，SmartScreen 点「更多信息 → 仍要运行」 |
| Windows | `Relic_windows.msi` | 批量部署用 |

安装包本身不含任何账号凭据，登录后才与服务器建立连接。

本仓库只托管安装包，不含源码。
