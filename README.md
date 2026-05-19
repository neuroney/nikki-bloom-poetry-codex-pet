<div align="center">
  <img src="assets/previews/idle.gif" width="128" alt="Nikki Bloom idle preview">

  <h1>Nikki Bloom Codex Pet</h1>

  <p>
    给 Codex 桌面端使用的 Q 版暖暖自定义宠物。灵感来自《闪耀暖暖》女主 Nikki / 暖暖穿着经典套装 <em>Bloom Poetry</em>（诗意绽放）的形象，并整理为 Codex 固定 8x9 精灵图格式。
  </p>

  <p>
    <a href="README.md"><strong>简体中文</strong></a>
    ·
    <a href="README_en.md">English</a>
    ·
    <a href="README_ja.md">日本語</a>
    ·
    <a href="README_ko.md">한국어</a>
  </p>

  <p>
    <a href="#安装"><img src="https://img.shields.io/badge/Codex-Custom%20Pet-111827?style=flat-square" alt="Codex Custom Pet"></a>
    <a href="#预览"><img src="https://img.shields.io/badge/Style-Chibi%203D%20Toy-ff8fb3?style=flat-square" alt="Chibi 3D Toy Style"></a>
    <img src="https://img.shields.io/badge/Atlas-8x9%20%7C%201536x1872-38bdf8?style=flat-square" alt="Atlas 8x9 1536x1872">
    <img src="https://img.shields.io/badge/States-9-8b5cf6?style=flat-square" alt="9 states">
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT%20%2B%20Notice-22c55e?style=flat-square" alt="MIT plus notice"></a>
  </p>
</div>

> 这是粉丝制作的自定义宠物资源，不是叠纸游戏、Infold Games 或《暖暖》系列的官方项目。

## 预览

![动作总览](assets/contact-sheet.png)

### 动作 GIF

| 待机 | 右移 | 左移 |
| --- | --- | --- |
| ![idle](assets/previews/idle.gif) | ![running right](assets/previews/running-right.gif) | ![running left](assets/previews/running-left.gif) |

| 招呼 | 跳跃 | 异常 / 失落 |
| --- | --- | --- |
| ![waving](assets/previews/waving.gif) | ![jumping](assets/previews/jumping.gif) | ![failed](assets/previews/failed.gif) |

| 等待确认 | 执行任务 | 完成反馈 |
| --- | --- | --- |
| ![waiting](assets/previews/waiting.gif) | ![running](assets/previews/running.gif) | ![review](assets/previews/review.gif) |

## 特色

- Q 版 3D 风格，保留 Nikki / 暖暖的粉色双辫、白色贝雷帽、温柔大眼与甜美少女感。
- 参考 *Bloom Poetry*（诗意绽放）造型：粉色格纹裙、酒红蝴蝶结、蕾丝边、白色袜鞋与细小花朵细节。
- 适配 Codex 自定义宠物固定规格：`1536x1872`、8 列 x 9 行、每格 `192x208`。
- 包含 9 个 Codex 状态：`idle`、`running-right`、`running-left`、`waving`、`jumping`、`failed`、`waiting`、`running`、`review`。
- `waiting` 是等待搭配师确认的期待姿态，`running` 是专注处理任务，`review` 是完成后查看结果。
- 已通过 atlas 校验：RGBA、透明背景、未使用格透明、无透明像素 RGB 残留。

## 安装

推荐从 Releases 下载 `nikki-bloom-codex-pet-v1.0.0.zip`。解压后会得到可直接安装的两个文件：

```text
pet.json
spritesheet.webp
```

把 `dist` 目录里的两个文件复制到你的 Codex 自定义宠物目录：

```text
$HOME/.codex/pets/nikki-bloom/
├── pet.json
└── spritesheet.webp
```

Windows 可放在：

```text
%CODEX_HOME%\pets\nikki-bloom\
├── pet.json
└── spritesheet.webp
```

本仓库已经包含可直接使用的文件：

- [dist/pet.json](dist/pet.json)
- [dist/spritesheet.webp](dist/spritesheet.webp)

重启 Codex 后，在自定义宠物列表中选择 **Nikki Bloom**。

## 文件结构

```text
.
├── assets/
│   ├── contact-sheet.png
│   ├── preview.png
│   └── previews/*.gif
├── dist/
│   ├── pet.json
│   ├── spritesheet.webp
│   ├── spritesheet.png
│   └── validation.json
├── docs/
│   └── sources-manifest.json
├── LICENSE
├── NOTICE.md
├── README.md
├── README_en.md
├── README_ja.md
└── README_ko.md
```

## 版本说明

当前发布版为 `v1.0.0`：

- 使用完整 9 行 Codex pet atlas。
- `running-left` 与 `running-right` 保持方向语义一致。
- 所有状态保持同一 Nikki Bloom 主视觉，不加入文字、UI、Logo 或官方素材截图。
- 根目录不包含生成中间层；`dist/` 是正式安装包，`assets/` 是预览资产。

Codex atlas 使用固定帧数排布，所以正式图集按 Codex 行规格填满，而不是把所有状态强行统一成相同帧数。

## 来源与授权

- 套装英文名与跨作命名依据记录在 [docs/sources-manifest.json](docs/sources-manifest.json)。
- Nikki、暖暖、《闪耀暖暖》与相关官方视觉设定归其权利方所有。
- 仓库没有打包官方立绘原图，仅发布整理后的 Codex 自定义宠物资源与预览图。
