# TIVS Device SDK 包格式

<!-- tivs-managed-docs:32b70d8c32ce8caeb2ccf9a42a8888b3b2182ccdc91361938124817fcb4524bb -->

## 包名

正式包名为：

```text
tivs-device-sdk__<target>__<toolchain-profile>__<vX.Y.Z>__p2p-...-cs-...-szopt-...-vdp-...-ext-...-nobs-...-noqrcode-....tgz
```

`target` 表示目标平台，`toolchain-profile` 表示编译工具链，`vX.Y.Z` 是上游
device-sdk tag；其余字段是构建参数。每个版本、每个 Builder 只发布登记的唯一规范参数包。

## 选择与校验

按 README 表格中的平台和工具链选择包。表格给出完整 SHA-256；GitHub Assets API
也在资产的 `digest` 字段提供同一摘要。下载后可执行：

```sh
shasum -a 256 <下载的文件>.tgz
```

## 压缩包内容

外层格式是 `tgz`，保留上游原包目录和内层压缩包，并在根目录增加：

- `README.md`：该平台的工具链、头文件、库、链接参数和 Demo 步骤。
- `build-info.json`：上游提交、Builder、工具链和实际构建参数。
- `MANIFEST.sha256`：包内普通文件的 SHA-256 清单。

同一 Release 可以继续增加新平台，已有平台资产不会覆盖。GitHub 自动生成的 Source code
ZIP／tar.gz 只包含下载仓文档，不是 SDK。
