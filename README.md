# KeySwitch 下载与更新

这里是 KeySwitch 的公开发布仓库，只存放应用安装包、版本清单和使用说明。应用源码由独立的私有仓库维护。

## 下载

在 [最新版本](https://github.com/Zhang94mz817/keySwitch-releases/releases/latest) 下载：

- Windows x64：`KeySwitch-windows-amd64.exe`
- Windows ARM64：`KeySwitch-windows-arm64.exe`
- macOS Intel / Apple Silicon：`KeySwitch-macos-universal.zip`

Windows 需要 Microsoft WebView2 Runtime。macOS 应用应先解压到“应用程序”目录。当前安装包未做商业代码签名或 Apple 公证。

每个安装包都有同名 `.sha256` 校验文件。版本清单包含版本、下载地址、文件大小和 SHA-256：

[latest.json](https://github.com/Zhang94mz817/keySwitch-releases/releases/latest/download/latest.json)

KeySwitch 0.6.0 起可直接通过公开清单升级，无需 GitHub 账号或 GitHub CLI。更早的版本需要手动下载一次新版。

私有源码的主分支更新后，自动测试和各平台构建全部通过才会发布新版本。发布流程只上传列出的安装包、校验文件和清单。
