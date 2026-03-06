# Claw 伴侣

**Claw 伴侣**让你在 **30 秒**内部署 Clawdbot，之后的一切都在浏览器里完成：配模型、接渠道、管服务——点点鼠标就搞定。

## 为什么选择 Claw 伴侣

- **30 秒部署**：一条命令自动搞定 Node.js、Clawdbot、管理面板和开机自启。
- **可视化管理**：模型配置、渠道管理、服务控制、日志查看，全部可视化操作。
- **200+ AI 模型**：接入任何 OpenAI 兼容 API。Claude、GPT、DeepSeek、Gemini、Grok——随便切。
- **8 大渠道**：钉钉、Telegram、Discord、Slack、微信、WhatsApp、Signal、飞书——一个面板全搞定。
- **本地运行**：所有数据留在你自己的机器上。私钥、聊天记录、配置文件——你的就是你的。
- **三平台通吃**：macOS、Linux、Windows 全支持。

## 三步上手

1. **运行安装命令**：一条命令自动安装所有依赖，创建服务，启动面板
2. **浏览器配置**：打开管理面板，填入 API Key，选择模型，添加渠道
3. **开始使用**：在钉钉、Telegram 等平台跟你的 AI 助手聊天

## 快速开始（安装）

在你的服务器上执行（建议用 root）：

```bash
ssh root@YOUR_VPS 'bash -s' < deploy.sh
```

自定义端口（默认 3210）：

```bash
COMPANION_PORT=3210 ssh root@YOUR_VPS 'bash -s' < deploy.sh
```

安装完成后，用浏览器打开：

- `http://YOUR_VPS_IP:3210`

## 下载

到 Releases 下载最新版：
<https://github.com/aicompaniondev/claw-companion-releases/releases>
