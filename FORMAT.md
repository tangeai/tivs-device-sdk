# TIVS Device SDK 包格式

<!-- tivs-managed-docs:12ddf3e5caf062fed1dd31e445cf150535138cc011e17ee32d38be3641876468 -->

## 包名

正式包名为：

```text
tivs-device-sdk__<target>__<toolchain-profile>__<vX.Y.Z>__p2p-...-cs-...-szopt-...-vdp-...-ext-...-nobs-...-noqrcode-....tgz
```

`target` 表示目标平台，`toolchain-profile` 表示编译工具链，`vX.Y.Z` 是上游
device-sdk tag；其余字段是完整有效构建参数。正式身份为 tag、Builder／工具链和完整有效参数组合；省略与显式默认归一为同一组合。一个版本可同时提供同平台的不同合法功能组合，每个组合只有一个包，同组合不可覆盖。旧版包名与资产保持原样。

## 选择与校验

按 README 表格中的平台、工具链和所需功能参数选择包。表格给出完整 SHA-256；GitHub Assets API
也在资产的 `digest` 字段提供同一摘要。下载后可执行：

```sh
shasum -a 256 <下载的文件>.tgz
```

## 压缩包内容

外层格式是 `tgz`，保留上游原包目录和内层压缩包，并在根目录增加：

- `README.md`：该平台的工具链、头文件、库、链接参数和 Demo 步骤。
- `build-info.json`：上游提交、Builder、工具链和实际构建参数。
- `MANIFEST.sha256`：包内普通文件的 SHA-256 清单。

同一 Release 可以继续增加新平台或不同参数组合，已有资产不会覆盖。GitHub 自动生成的 Source code
ZIP／tar.gz 只包含下载仓文档，不是 SDK。
