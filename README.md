# 久远寺有珠 · Codex 动画小人

黑色冬装、短黑发与帽沿上的蓝色小鸟。默认待机为端坐品茶，包含轻轻举杯、闭眼啜饮与眨眼。

![端坐品茶](previews/idle.gif)

## 安装

1. 在本仓库点击 **Code → Download ZIP**，解压下载的文件。
2. 在你的 Codex 用户目录中创建 `pets/kuonji-alice-black-20261004/`。
3. 将仓库根目录的 **`pet.json`** 和 **`spritesheet.webp`** 放入该文件夹。
4. 在 Codex 的 **设置 → Pets** 中刷新并选择「久远寺有珠」。

Windows 的默认安装位置：

```text
%USERPROFILE%\.codex\pets\kuonji-alice-black-20261004\
├── pet.json
└── spritesheet.webp
```

如果小人已迁移到云端宠物库，替换本地文件不会同步修改云端版本；云端版本需要单独更新为仓库中的 `spritesheet.webp`。

## 动作预览

下载后，用浏览器打开 [preview.html](preview.html)，可以同时查看全部动作并切换预览底色。

| 动作 | 帧数 | 预览 |
| --- | ---: | --- |
| 端坐品茶／默认待机 | 6 | [idle.gif](previews/idle.gif) |
| 向右跑动 | 8 | [running-right.gif](previews/running-right.gif) |
| 向左跑动 | 8 | [running-left.gif](previews/running-left.gif) |
| 挥手 | 4 | [waving.gif](previews/waving.gif) |
| 跳跃 | 5 | [jumping.gif](previews/jumping.gif) |
| 失落 | 8 | [failed.gif](previews/failed.gif) |
| 等待输入 | 6 | [waiting.gif](previews/waiting.gif) |
| 工作中 | 6 | [running.gif](previews/running.gif) |
| 检查结果 | 6 | [review.gif](previews/review.gif) |

## 文件规格

- 透明 WebP 图集，`1536 × 1872` 像素。
- v1 布局：8 列 × 9 行，每格 `192 × 208` 像素。
- 57 个有效动画帧；15 个未使用的格子完全透明。
- 已通过结构、透明背景、动画与独立视觉检查。
- 喝茶版本只修改默认待机；其余八组动作保留原版像素。

`spritesheet.webp` 的 SHA-256：

```text
93b68fe884096aff2e68353ef7099efcb6a2bb33a37b3184ed616e5eca4a078b
```

角色为久远寺有珠。本仓库提供日系 Q 版动画小人文件。

