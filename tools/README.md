# 随仓库提供的 age

本仓库内的 Windows、Apple Silicon Mac 和 Intel Mac 可执行文件均来自 [age 官方 v1.3.2 发布页](https://github.com/FiloSottile/age/releases/tag/v1.3.2)。下载时与 GitHub 官方发布 API 中的 SHA-256 digest 核对：

| 平台 | 官方归档文件 | SHA-256 |
| --- | --- | --- |
| Windows x64 | `age-v1.3.2-windows-amd64.zip` | `f48d8f8f9ebe903ab5027ed067652f2cc1db94bc206976430133b905dcd8e8c7` |
| macOS Apple Silicon | `age-v1.3.2-darwin-arm64.tar.gz` | `e2020b073c44f692685a24d6abc378817eb81ffaaf49fd0531ef8565f767f2f5` |
| macOS Intel | `age-v1.3.2-darwin-amd64.tar.gz` | `1d1e4bc66e1427edad7739ae7616157de0e79db8b6d2a1497d7d9925fb06a539` |

各平台目录下保留了随官方发布包提供的许可证文件。新生只需运行仓库根目录对应系统的 `submit.ps1` 或 `submit.sh`。
