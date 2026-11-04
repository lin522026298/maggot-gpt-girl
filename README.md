# 蛆版 GPT 娘 / Maggot GPT Girl

视频《零门槛实现涂装自由： AI 驱动的涂装制作工作流》中使用的自定义桌宠。

白紫发、双角、奶白分节虫身，通过收缩、拱起和伸展蠕动移动。

![待机与慢眨眼预览](previews/idle.gif)

## 下载

- [下载完整桌宠包 ZIP](https://github.com/lin522026298/maggot-gpt-girl/releases/latest/download/maggot-gpt-girl.zip)
- [查看发布版本](https://github.com/lin522026298/maggot-gpt-girl/releases)
- [原始透明图集](maggot-gpt-girl/spritesheet.webp)
- [桌宠配置](maggot-gpt-girl/pet.json)
- [笑脸原帧](previews/smile.png)

ZIP 中的目录结构：

```text
maggot-gpt-girl/
├── pet.json
└── spritesheet.webp
```

包内提供现有 Codex v2 本地自定义桌宠使用的配置与图集。解压后可以把整个
`maggot-gpt-girl` 文件夹交给你的 Agent，按所用客户端支持的自定义桌宠方式安装。
需要使用单独图集的场景，可以直接下载 `spritesheet.webp`。

本次发布保留原始桌宠文件。视频所用下载版与此安装版的 WebP 压缩大小不同，
解码后的 RGBA 像素完全一致；没有重新绘制桌宠。

## 图集说明

- 图集：1536 × 2288，RGBA 透明背景。
- 网格：8 列 × 11 行；每格 192 × 208。
- 第 0 行为待机，第 1、2 行为左右蠕动；其余包含挥手、跳跃、工作等状态及方向注视。
- 行号从 0 开始。详细帧数见 [atlas-layout.json](atlas-layout.json)。
- 封面使用的闭眼微笑原帧位于第 0 行、第 4 列。
- GIF 是展示预览，实际动作速度由使用它的客户端决定。

## 校验

仓库文件校验见 [SHA256SUMS.txt](SHA256SUMS.txt)。发布页同时提供 ZIP 的 SHA-256 文件。
本仓库只包含桌宠配置、图集和预览，不含账号凭据、会话数据或本机配置。

## Related project

[Forza Livery Agent Workflow](https://github.com/lin522026298/FH6-Livery-Agent-Workflow)

This repository contains the original custom pet configuration, transparent sprite
sheet and a small animation preview. Download the ZIP from Releases and give the
extracted folder to your Agent for installation in a compatible client.
