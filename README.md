# pi-ac-blue

A cool cyan-on-navy dark theme for [Pi](https://pi.dev), with an instrument-panel mood borrowed from tactical mission-briefing interfaces.

Pi 的冷色深蓝主题：近黑海军蓝底、青蓝描边与琥珀点缀，气质接近战术简报界面。

One theme, `ac-blue`. Backgrounds stay near-black navy so panels read as lit glass, the accent line stays a single cyan, and warm colors are rationed: amber appears only on list bullets, numbers, `warning`, and bash mode.

## Install

```bash
pi install npm:pi-ac-blue
```

Restart Pi or run `/reload` after installing.

## Usage

Select `ac-blue` in `/settings` → **Theme**, or use it for a single run:

```bash
pi --use-theme ac-blue
```

To keep it as the default, set it in the settings file:

```json
{
  "theme": "ac-blue"
}
```

## Palette

| Role | Color | Used for |
|---|---|---|
| Background | `#0a1119` | Base surface |
| Panel | `#0e1822` | Tool boxes, scrollbar track |
| Border | `#1d3a4e` | Normal borders, rules, quote bars |
| Accent | `#3fb6dc` | Cursor, logo, links, headings, keywords |
| Text | `#d3e2ec` | Body text |
| Muted / Dim | `#8aa3b6` / `#5d7386` | Secondary and tertiary text, comments |
| Amber | `#ffb02e` | Warnings, numbers, list bullets, bash mode |
| Green | `#57c9a0` | Success, strings, inline code, diff additions |
| Red | `#ff5340` | Errors, diff removals |
| Blue | `#6aa8e8` | Type names |
| Violet | `#a48ce0` | Custom message labels |

The full definition, including message backgrounds and the thinking-level ramp, lives in [`themes/ac-blue.json`](./themes/ac-blue.json).

## Appearance

The theme targets dark terminals (`"appearance": "dark"`). It uses truecolor values directly; on 256-color terminals Pi approximates them, and the palette degrades reasonably because the accent hues are separated by lightness as well as hue.

## Disclaimer

This is an unofficial, fan-made color theme. It is **not affiliated with, endorsed by, or sponsored by** any game developer or publisher. No game assets — logos, fonts, artwork, or screenshots — are included; the package contains color values only. Any resemblance to a particular interface is a stylistic homage, not a claim of association.

## License

MIT

---

## 中文

Pi 的冷色深蓝主题：近黑海军蓝底、青蓝描边与琥珀点缀，气质接近战术简报界面。

只包含一个主题 `ac-blue`。底色统一压到近黑海军蓝，让面板像发光的玻璃；强调色只有一种青蓝；暖色严格控制，琥珀色只出现在列表标记、数字、`warning` 和 bash 模式上。

### 安装

```bash
pi install npm:pi-ac-blue
```

安装后重启 Pi 或执行 `/reload`。

### 用法

在 `/settings` → **Theme** 中选择 `ac-blue`，或仅对本次运行生效：

```bash
pi --use-theme ac-blue
```

想设为默认，写入 settings 文件：

```json
{
  "theme": "ac-blue"
}
```

### 配色

| 角色 | 颜色 | 用途 |
|---|---|---|
| 背景 | `#0a1119` | 基底 |
| 面板 | `#0e1822` | 工具框、滚动条轨道 |
| 边框 | `#1d3a4e` | 常规边框、分隔线、引用条 |
| 强调 | `#3fb6dc` | 光标、logo、链接、标题、关键字 |
| 正文 | `#d3e2ec` | 主体文字 |
| 次要 / 弱化 | `#8aa3b6` / `#5d7386` | 次级与三级文字、注释 |
| 琥珀 | `#ffb02e` | 警告、数字、列表标记、bash 模式 |
| 绿 | `#57c9a0` | 成功、字符串、内联代码、新增行 |
| 红 | `#ff5340` | 错误、删除行 |
| 蓝 | `#6aa8e8` | 类型名 |
| 紫 | `#a48ce0` | 自定义消息标签 |

完整定义（含消息背景色与思考级别渐变）见 [`themes/ac-blue.json`](./themes/ac-blue.json)。

### 适用环境

面向深色终端（`"appearance": "dark"`）。主题直接使用 truecolor 色值；在 256 色终端上 Pi 会做近似，但由于强调色在明度上也拉开了差距，降级效果仍可接受。

### 声明

本项目是非官方的粉丝配色主题，**与任何游戏开发商或发行商无关**，也未获得其认可或赞助。包内不含任何游戏素材（logo、字体、美术或截图），只有颜色数值。与某个界面的相似属于风格致敬，不代表任何关联。

### 许可证

MIT
