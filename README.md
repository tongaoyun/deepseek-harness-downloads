# DeepSeek Harness Downloads

Windows 与 macOS 安装包下载，无需 GitHub 登录。此仓库仅分发安装包和校验清单。

## 下载 / Downloads

[下载页面 / Download Releases](https://github.com/tongaoyun/deepseek-harness-downloads/releases)

选择页面顶部的最新开发版本，在该版本的 Assets 中按平台下载安装包。每个版本同时提供 `build-manifest.json` 和 `SHA256SUMS.txt`。

Choose the newest development release at the top of the page and download the installer for your platform from its Assets. Each release includes `build-manifest.json` and `SHA256SUMS.txt`.

| 平台 / Platform | 安装包文件名结尾 / Installer Filename Suffix |
| --- | --- |
| Windows x64 | `-win-x64-unsigned.exe` |
| Mac Apple Silicon | `-mac-arm64-unsigned.dmg` |
| Mac Intel | `-mac-x64-unsigned.dmg` |

## 安装 / Installation

Windows 下载后打开 EXE 安装；Mac 下载后打开 DMG，将应用拖入 Applications。Mac 芯片类型可在“关于本机”中查看。

On Windows, open the EXE installer. On macOS, open the DMG and drag the app to Applications. Check About This Mac to identify your chip.

开发验收版未签名、未进行 macOS 公证。系统可能显示来源确认或阻止打开；确认来源后使用系统提供的安全设置进行处理。安装包的公开下载不替代应用内的员工登录。

Development builds are unsigned and lack macOS notarization. The operating system may request confirmation or block opening them; use the operating system's security settings after verifying the source. Public installer downloads do not replace employee sign-in inside the application.

Release 文件不会随原构建的 Actions 产物十四天到期而删除。

Release files are independent of the original Actions artifacts' fourteen-day expiration.
