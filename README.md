# Osborne

终端重度使用者。用 tmux + Neovim 把日常操作磨到顺手，用 Go 写解决自己问题的小工具，最近在把 AI Agent 塞进真实工作流。

> 先给自己用，再开源。能用单文件解决就不引依赖。

---

## 🖥 终端环境

| 仓库 | 说明 |
|---|---|
| [tmux-config](https://github.com/OsborneWang/tmux-config) | `macOS → SSH → Ubuntu` 场景的 tmux 配置：vim 风格切窗格、主窗格布局、扩展键、剪贴板图片路径直插 |
| [self_config](https://github.com/OsborneWang/self_config) | 跨服务器同步的终端配置（tmux / yazi / Neovim），基于 OSC 52 打通 `kitty/ghostty → SSH → tmux → 远端应用` 的剪贴板链路 |
| [neovim-self](https://github.com/OsborneWang/neovim-self) | 自己整理的 Neovim 配置 |

## 🛠 命令行工具

| 仓库 | 说明 |
|---|---|
| [goSSH](https://github.com/OsborneWang/goSSH) | 跨平台 SSH CLI：服务器管理、交互 Shell、远程命令、SFTP 传输；自动在新标签页打开会话（Windows Terminal / iTerm2 / GNOME Terminal 等） |
| [gocc](https://github.com/OsborneWang/gocc) | goConnect — 轻量 SSH 连接管理器，JSON 存储，按名字一键连 |
| [github_down](https://github.com/OsborneWang/github_down) | GitHub 下载加速工具 |

## 🤖 AI 工作流

| 仓库 | 说明 |
|---|---|
| [journal-config](https://github.com/OsborneWang/journal-config) | 活在 tmux 里的个人日志 / 今日看板 / 日报月报。Python 单文件、零第三方依赖；AI 只做无状态一次性调用，所有数字由脚本统计 |
| [pi-config](https://github.com/OsborneWang/pi-config) | pi 的个人配置同步：settings、快捷键、主题、自定义 model provider |
| [pi-rpc-chat](https://github.com/OsborneWang/pi-rpc-chat) | 用浏览器聊天框驱动本机 pi RPC 模式的局域网 Web 应用 |
| [super_personal_agent](https://github.com/OsborneWang/super_personal_agent) | Go 实现的个人 Agent 实验 |

---

## 🔨 日常技术栈

`Go` · `TypeScript` · `Python` · `Shell` · `Lua`

**常用**：tmux · Neovim · yazi · Ghostty · macOS · Ubuntu

---

## 📌 最近在做

- 把 journal 的采集—结构—派生三层拆分跑通，AI 只负责叙述，不碰原始记录
- 统一 tmux / Neovim / yazi 的跨机同步，减少换机器时的重建成本
- 探索 Agent 在终端里的最小可用形态：无状态调用 > 长驻会话

---

## 📫 联系

osborne.wangxubo@gmail.com
