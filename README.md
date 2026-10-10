<div align="center">
<img src="public/dukoai.svg" width="96" alt="DukoAI Logo" />
</div>

# DukoAI Connect

DukoAI 的本地 API 接入工具，一键配置 Claude / Codex。默认站点为 **DukoAI**，默认地址为 **https://dukoai.com**。

## 下载与使用

| 系统 | 下载 | 打开方式 |
| --- | --- | --- |
| Windows 10 / 11 · x64 | [Windows 免安装 ZIP](https://dukoai.com/downloads/DukoAI-Connect-0.1.0-Windows-x64-portable.zip) | 完整解压，打开 `DukoAI Connect.exe` |
| macOS · Apple Silicon | 构建产物核验中，正式上线后从 DukoAI 网站下载 | 解压后打开 `DukoAI Connect.app`，可拖入「应用程序」 |

1. 打开 DukoAI Connect，选择 DukoAI 站点。
2. 选择需要配置的 Claude / Codex 客户端。
3. 输入在 [DukoAI](https://dukoai.com) 创建的 API 密钥。
4. 获取并选择模型，然后导入。
5. 完全退出目标客户端，再重新打开并新建会话。

Mac 包适用于 M 系列芯片，不支持 Intel Mac。目前采用 ad-hoc 签名，尚未完成 Apple Developer ID 签名与公证。

## 构建 macOS 版本

在本仓库的 Actions 页面选择 `Build DukoAI Connect macOS`，点击 `Run workflow`。完成后下载 `DukoAI-Connect-macOS-arm64` 构建产物。

构建时使用 `public/dukoai.svg` 生成 DukoAI 应用图标。

## 开源与版权

本定制版基于 [superpilot69/supergpt-connect](https://github.com/superpilot69/supergpt-connect)，采用 MIT 许可证。原作者版权及第三方声明保留在 [LICENSE](LICENSE)、[DUKOAI-NOTICE.md](DUKOAI-NOTICE.md) 和 `licenses/` 中。
