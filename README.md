# TIVS Device SDK 公开下载仓

这里提供 TIVS Device SDK 的正式安装包。本仓只用于下载，不提供 SDK 源码。

[全部版本](../../releases) · [版本变化](CHANGELOG.md) · [包名与校验](FORMAT.md)

## 当前正式版本

<!-- tivs-downloads:start -->
**v1.375.4**

| 平台 | 工具链 | 标准参数 | 完整文件名 | SHA-256 |
| --- | --- | --- | --- | --- |
| `fullhan-fh8626` | `arm-fullhanv3-linux-uclibcgnueabi-b5` | `p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n` | [`tivs-device-sdk__fullhan-fh8626__arm-fullhanv3-linux-uclibcgnueabi-b5__v1.375.4__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz`](https://github.com/tangeai/tivs-device-sdk/releases/download/v1.375.4/tivs-device-sdk__fullhan-fh8626__arm-fullhanv3-linux-uclibcgnueabi-b5__v1.375.4__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz) | `fdb4e8cf05920541b69165b405ac8cc0d6c93a0e1750519178971de7fcca65d9` |
| `goke-gk7205v500` | `arm-gcc7.3-linux-musleabi` | `p2p-kcp-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n` | [`tivs-device-sdk__goke-gk7205v500__arm-gcc7.3-linux-musleabi__v1.375.4__p2p-kcp-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz`](https://github.com/tangeai/tivs-device-sdk/releases/download/v1.375.4/tivs-device-sdk__goke-gk7205v500__arm-gcc7.3-linux-musleabi__v1.375.4__p2p-kcp-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz) | `ea19d7a0de509d66b6f9daecf5908f4acff52d89011e359a7212906f077b5cab` |
| `linux-x86_64` | `gcc11-glibc2.35` | `p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n` | [`tivs-device-sdk__linux-x86_64__gcc11-glibc2.35__v1.375.4__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz`](https://github.com/tangeai/tivs-device-sdk/releases/download/v1.375.4/tivs-device-sdk__linux-x86_64__gcc11-glibc2.35__v1.375.4__p2p-webrtc2-cs-sliced-szopt-0-vdp-n-ext-n-nobs-n-noqrcode-n.tgz) | `0d87c818338ce006ccbc06f2e1a0d8cf9e4b6bd3ac0cd43bdd0cc46b61a2c149` |
<!-- tivs-downloads:end -->

按目标平台和工具链选择一行下载。下载后先核对 SHA-256，再解压并阅读包内
`README.md`；它给出该平台的工具链、头文件、静态库、链接参数和 Demo 步骤。

GitHub 页面自动生成的 **Source code (zip)** 和 **Source code (tar.gz)** 只是本下载仓
的文档快照，不是 SDK。

<details><summary>当前版本基线</summary>

<!-- tivs-build-baseline:start -->
```json
{
  "release_tag": "v1.375.4",
  "schema": 1,
  "sdk_commit": "29d80bb32d5ab484dbfed5844b16073bb1cedc0d",
  "tgsysadpt_commit": "247fecc0ba8501c14877ea5ddc1b5814036333ea",
  "tgwebrtc_commit": "64b74c0a3be692f03bd42ded3a6ebbcb1162ce24"
}
```
<!-- tivs-build-baseline:end -->

</details>
