# claw-companion

Claw 伴侣（Web 管理面板）。

## 安装（推荐：Release 包，无需源码/无需 git）

**Canonical 安装目录：`/opt/claw-companion`**

```bash
ssh root@YOUR_VPS 'bash -s' < deploy.sh
```

自定义端口：

```bash
COMPANION_PORT=3210 ssh root@YOUR_VPS 'bash -s' < deploy.sh
```

> 旧版可能安装在 `/root/.openclaw/companion`。更新时会自动识别并尽量迁移到 `/opt/claw-companion`（或保持原目录）。

## 更新

面板内：系统 → **检查更新 / 更新 Claw伴侣**（优先从本仓库的 GitHub Release 更新）。

如果你需要命令行更新（可选）：

```bash
curl -fsSL https://raw.githubusercontent.com/aicompaniondev/claw-companion/main/scripts/release-update.sh | bash
```

## 版本与下载

请到 Releases 页面下载对应版本：
<https://github.com/aicompaniondev/claw-companion-releases/releases>
