# AI 账号管理器

在一个窗口里管理多个 Claude / Codex 账号与中转站，一键切换官方桌面端的登录账号，对话记录不受影响。

- 显示每个账号 5 小时和每周额度的用量
- 可选内置代理：只让 Claude / Codex / ChatGPT 相关流量走你自己的节点，其他直连
- 环境检测：检查出口 IP、时区、语言、浏览器设置是否适合使用 Claude

## 下载

到右侧 **[Releases](../../releases/latest)** 下载 `AI账号管理器-v版本号-windows.7z`。

压缩包已加密，**需要密码才能解压**。密码请向发布者索取。

## 安装

1. 用 [7-Zip](https://www.7-zip.org/) 或 Bandizip 解压，输入密码（Windows 自带的解压不支持加密的 7z）。
2. 把解压出来的整个文件夹放在固定位置，双击 `AI账号管理器.exe`。
3. 第一次运行如果出现“Windows 已保护你的电脑”，点“更多信息” → “仍要运行”。程序没有购买代码签名证书，所以会有这个提示。

系统要求：Windows 10 / 11（64 位）。目前没有 macOS 版本。

## 隐私

账号和订阅只保存在你自己电脑的 `%USERPROFILE%\.ai-account-manager\` 里，订阅地址用 Windows 自带的加密保存。程序不会把你的数据上传到第三方服务器。

## 第三方组件

压缩包内的 `core\mihomo.exe` 是开源代理内核 [mihomo](https://github.com/MetaCubeX/mihomo)（v1.19.33，未修改），按 GPL-3.0 协议分发，许可证随包附带（`core\mihomo-LICENSE.txt`）。
