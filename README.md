# TIVS Device SDK 公开下载仓

这里提供 TIVS Device SDK 的正式安装包。本仓只用于下载，不提供 SDK 源码。

[全部版本](../../releases) · [版本变化](CHANGELOG.md) · [包名与校验](FORMAT.md)

## 当前正式版本

<!-- tivs-downloads:start -->
**v1.375.6**

| 平台 | 工具链 | 有效参数 | 完整文件名 | SHA-256 |
| --- | --- | --- | --- | --- |
| `augentix-hc1703` | `arm-augentix-linux-uclibcgnueabihf` | `p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n` | [`tivs-device-sdk__augentix-hc1703__arm-augentix-linux-uclibcgnueabihf__v1.375.6__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz`](https://github.com/tangeai/tivs-device-sdk/releases/download/v1.375.6/tivs-device-sdk__augentix-hc1703__arm-augentix-linux-uclibcgnueabihf__v1.375.6__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz) | `ad074cf0088dba13beac3c4284443a968dda9935c9a7e7cb9a4690272b6699dc` |
| `novatek-nt96562` | `arm-ca9-linux-uclibcgnueabihf-6.5` | `p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n` | [`tivs-device-sdk__novatek-nt96562__arm-ca9-linux-uclibcgnueabihf-6.5__v1.375.6__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz`](https://github.com/tangeai/tivs-device-sdk/releases/download/v1.375.6/tivs-device-sdk__novatek-nt96562__arm-ca9-linux-uclibcgnueabihf-6.5__v1.375.6__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz) | `f7ccd02c154289597d9d2d67395bafb30c349e1b5b7c6326509c9a9bfcefb41d` |
| `novatek-nt96562` | `arm-ca9-linux-uclibcgnueabihf-6.5` | `p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-y-nobs-n-noqrcode-n` | [`tivs-device-sdk__novatek-nt96562__arm-ca9-linux-uclibcgnueabihf-6.5__v1.375.6__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-y-nobs-n-noqrcode-n.tgz`](https://github.com/tangeai/tivs-device-sdk/releases/download/v1.375.6/tivs-device-sdk__novatek-nt96562__arm-ca9-linux-uclibcgnueabihf-6.5__v1.375.6__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-y-nobs-n-noqrcode-n.tgz) | `0fe12a68b260c48f3b684ae0868885b0ba2bac83b062c3556d472112e0c7fd03` |
<!-- tivs-downloads:end -->

按目标平台、工具链和所需功能参数选择一行下载。同一平台可能提供不同参数组合；包名和 build-info.json 记录完整有效值。下载后先核对 SHA-256，再解压并阅读包内
`README.md`；它给出该平台的工具链、头文件、静态库、链接参数和 Demo 步骤。

GitHub 页面自动生成的 **Source code (zip)** 和 **Source code (tar.gz)** 只是本下载仓
的文档快照，不是 SDK。

<details><summary>当前版本基线</summary>

<!-- tivs-build-baseline:start -->
```json
{
  "release_tag": "v1.375.6",
  "schema": 1,
  "sdk_commit": "296b088a9e16943b96b441bf9c092fd6375f0df6",
  "tgsysadpt_commit": "247fecc0ba8501c14877ea5ddc1b5814036333ea",
  "tgwebrtc_commit": "5b43be027a43796807567e9a9ee71e8848358323"
}
```
<!-- tivs-build-baseline:end -->

</details>
