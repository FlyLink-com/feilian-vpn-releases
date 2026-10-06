# 飞连 VPN 发布资料 / Feilian VPN Releases

本仓库分发飞连 VPN Android 安装包、每版完整对应源码、公开签名证书及校验资料。

## 下载与校验

在本仓库的 Releases 中选择版本。每个正式版本提供：

- `feilian-vpn-v<版本>.apk`：正式签名 Android 安装包。
- `feilian-vpn-v<版本>-corresponding-source.zip`：该 APK 对应的项目源码、原生组件、依赖源码和许可材料。
- `feilian-vpn-release-certificate.der`：公开发布证书，不含私钥。
- `feilian-vpn-v<版本>-release-manifest.json`：包名、版本、源码提交、证书指纹及文件摘要。
- `SHA256SUMS`：附件 SHA-256 校验值。

GitHub 自动生成的 “Source code (zip/tar.gz)” 只包含这个资料仓库的文档。完整 Android 对应源码是单独的 `-corresponding-source.zip` 附件；组件许可证、版权声明和重建说明见该附件。

正式包名为 `com.gccwebos.android`，支持 Android 8.0 及以上；具体版本以已发布的 Release 和清单为准。现有 candidate/debug 测试包具有独立身份；正式版首次安装后需自行登录或通过正常入口导入配置。后续正式升级保持同包名和签名。

网站：https://gccwebos.com/

## Release assets

Download the signed APK and its complete corresponding source archive from the selected release. Check `SHA256SUMS` and the release manifest before installation. The DER file is a public certificate, not a private signing key. GitHub's automatically generated source archives contain only this distribution repository's documentation; use the separately attached `-corresponding-source.zip` for the Android project and dependency sources, licenses and rebuild instructions.

Stable website availability and update metadata are published separately after verification. A draft or prerelease does not mean the website download channel is available. Read each release's validation scope and known limitations.
