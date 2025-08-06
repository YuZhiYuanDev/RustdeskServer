# RustDesk 服务器程序

[![build](https://github.com/YuZhiYuanDev/RustdeskServer/actions/workflows/build.yaml/badge.svg)](https://github.com/YuZhiYuanDev/RustdeskServer/actions/workflows/build.yaml)

[**下载**](https://github.com/YuZhiYuanDev/RustdeskServer/releases)

[**手册**](https://rustdesk.com/docs/cn/self-host/)

[**FAQ**](https://github.com/YuZhiYuanDev/RustdeskServer/wiki/FAQ)

自托管您自己的 RustDesk 服务器，它是免费和开源的。

## 如何手动构建

```bash
cargo build --release
```

将在目标/发布中生成三个可执行文件。

- hbbs - RustDesk ID/Rendezvous 服务器
- hbbr - RustDesk 中继服务器
- rustdesk-utils - RustDesk CLI 实用程序

您可以在 [Releases](https://github.com/YuZhiYuanDev/RustdeskServer/releases) 页面上找到更新的二进制文件。

## 安装

请遵循此 [文档](https://rustdesk.com/docs/cn/self-host/rustdesk-server-oss/)

