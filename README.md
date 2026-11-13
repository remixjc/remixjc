<h1 align="center">Hi, I'm Jacob 👋</h1>

<p align="center">
  <strong>把复杂流程，做成顺手的工具。</strong>
</p>

<p align="center">
  Web 应用 · 跨平台桌面工具 · macOS 原生开发
</p>

<p align="center">
  <a href="https://github.com/remixjc">GitHub</a> ·
  <a href="https://github.com/remixjc?tab=repositories">项目仓库</a> ·
  <a href="https://github.com/remixjc/remixjc/issues">交流与联系</a>
</p>

---

## 关于我

我是 **Jacob（@remixjc）**，一名来自中国的开发者。

我喜欢从日常使用和开发工作中的具体问题出发，把重复操作、分散配置和复杂流程整理成易用的软件。公开项目涵盖打印工作台、网络与设备管理、浏览器端工具，以及 macOS 原生应用。

我关注界面背后的完整体验：功能是否解决问题、数据如何保存、应用怎样部署，以及用户遇到错误时能否得到清晰反馈。**实用、清晰、尊重用户对数据的控制**，是我希望持续做好产品的方向。

## 精选项目

### [Magic Printer · 魔法打印大师](https://github.com/remixjc/Magic-Printer)

**本地优先的跨平台打印工作台。**

将桌面托盘、本地 Web 界面与系统打印服务整合起来，在 Windows、macOS 和 Linux 上提供文件上传、预览、参数设置和打印提交。

- 文件与打印记录保存在本机；可主动开启局域网访问，通过配对码连接其他设备。
- 支持 PDF、图片和 Office 文件处理，包含打印机能力识别与 A4 半张发票版式。

`TypeScript` `Electron` `Fastify` `SQLite`

[查看源码](https://github.com/remixjc/Magic-Printer) · [项目介绍](https://remixjc.github.io/Magic-Printer/)

### [TunnelOne · 隧行](https://github.com/remixjc/TunnelOne)

**让 WireGuard 隧道与系统代理协同工作的 macOS 原生客户端。**

基于 WireGuard 官方 macOS 客户端扩展，为每个隧道提供独立的代理偏好，连接时沿用用户已有的系统代理配置。

- 支持 HTTP、HTTPS、SOCKS、PAC 与绕过规则，包含连接验证和代理变化同步。
- 结合菜单栏、钥匙串与系统扩展，提供签名、公证和通用架构发布流程；目前处于 Beta 阶段。

`Swift` `AppKit` `Network Extension` `WireGuard`

[查看源码](https://github.com/remixjc/TunnelOne) · [项目介绍](https://remixjc.github.io/TunnelOne/)

### [DockerHelper](https://github.com/remixjc/dockerHelper)

**自托管、跨平台的 Docker Web 管理工作台。**

通过统一界面管理容器、镜像、Compose、网络和存储卷，使用 Go 后端直接对接 Docker Engine API。

- 静态界面内嵌于可执行文件，简化部署；支持本地引擎与远程 TLS 连接。
- 提供日志、资源统计、后台任务和操作审计；目前处于预览阶段。

`Go` `JavaScript` `Docker Engine API` `Docker Compose`

[查看源码](https://github.com/remixjc/dockerHelper) · [项目介绍](https://remixjc.github.io/dockerHelper/)

### [Preference Coordinates · 偏好坐标](https://github.com/remixjc/preference-coordinates)

**隐私优先的四维人格偏好探索工具。**

通过情境题与连续维度结果，帮助用户观察自己的偏好，提供极速版、标准版、历史对比和结果卡片导出。

- 答题、计分与历史记录均在浏览器本地完成，无需注册账号。
- 使用版本化计分逻辑与可复现题组，配套类型检查、单元测试和静态站点检查。

`TypeScript` `React` `Next.js` `Vitest`

[查看源码](https://github.com/remixjc/preference-coordinates) · [在线体验](https://remixjc.github.io/preference-coordinates/)

<sub>偏好坐标用于自我探索；原创题库尚未完成心理测量效度验证，不用于心理诊断。</sub>

## 更多工具

| 项目 | 解决的问题 | 技术方向 |
| --- | --- | --- |
| [WireGuard Tray](https://github.com/remixjc/wireguard-tools-gui-for-mac) | 为 `wg` / `wg-quick` 提供 macOS 状态栏管理界面，支持隧道启停、配置查看及钩子配置编辑 | Swift · macOS |
| [Redmi AX3000 Controller](https://github.com/remixjc/Redmi_AX3000_Controller) | 通过局域网接口监控路由器与联网设备，查看实时速率并管理设备 | Python · 设备管理 |
| [ComHelper Web](https://github.com/remixjc/comHelper) | 在浏览器中完成串口收发、HEX 调试、波形查看与日志导出，目前处于 Alpha 阶段 | TypeScript · Web Serial |

## 技术与实践

| 方向 | 项目中使用的技术与方法 |
| --- | --- |
| Web 开发 | TypeScript、JavaScript、React、Next.js |
| 桌面与原生应用 | Electron、Swift、AppKit、macOS 系统集成 |
| 服务与本地数据 | Go、Python、Fastify、SQLite、浏览器本地存储 |
| 网络与设备 | WireGuard、系统代理、Docker Engine API、Web Serial、局域网设备接口 |
| 工程交付 | GitHub Actions、自动化构建与发布、GitHub Pages、类型检查与测试 |

## 我重视的开发方式

- **从问题出发**：先明确使用场景，再决定功能与技术方案。
- **让数据可控**：优先考虑本地处理、自托管和清晰的访问授权。
- **把交付做完整**：让代码、界面、文档、安装与错误反馈共同构成可用的工具。

## 交流与联系

欢迎交流跨平台工具、macOS 应用、网络管理和浏览器端开发，也欢迎分享你遇到的具体问题。

项目相关的反馈与建议，请在对应仓库提交 Issue；其他交流可以通过 [个人主页仓库的 Issues](https://github.com/remixjc/remixjc/issues) 联系我。

---

<p align="center">
  <sub>Build useful things. Make everyday work simpler.</sub>
</p>
