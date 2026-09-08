# wx-voip-demo

微信 VoIP 设备模拟器二进制发布仓库。本仓库不提供源代码。

## 下载

请从 [Releases](https://github.com/tangeai/wx-voip-demo/releases) 下载对应平台的发布包：

- 模拟器版本：`v2.3.2`
- TiRTC 版本：`v2.3.0`

- macOS Apple Silicon：`wx-voip-demo-darwin-arm64-<TiRTC版本>-<模拟器版本>.tar.gz`
- Linux x86_64：`wx-voip-demo-linux-amd64-<TiRTC版本>-<模拟器版本>.tar.gz`

每个 Release 同时提供 `SHA256SUMS`。下载后可验证文件完整性：

```bash
shasum -a 256 -c SHA256SUMS
```

## 使用

解压对应平台的压缩包，在发布目录中运行：

```bash
./device-simulator/wxvoip-device-simulator.out --help
```
