# maclike-fcitx5-themes

[🇨🇳 中文](./READ.md) | [🇬🇧 English](./README.en.md)

一个简洁的 Fcitx5 主题，风格偏 macOS，可用于 Fcitx5（包括常见的 Fcitx5 Rime 场景）。

## 预览

![Theme Preview](./image/macOS.png)

## 环境要求

- 已安装并启用 Fcitx5

## 安装

1. 克隆仓库

```bash
git clone https://github.com/moyuwangzi/maclike-fcitx5-themes.git
cd maclike-fcitx5-themes
```

2. 复制主题到本地主题目录

```bash
mkdir -p ~/.local/share/fcitx5/themes
cp -r macOS-dark ~/.local/share/fcitx5/themes/macOS-dark 
```

## 启用主题

1. 打开 Fcitx5 配置工具。
2. 进入附加组件，找到经典用户界面（Classic User Interface）。
3. 将主题设置为 `macOS-dark`。
4. 重新加载 Fcitx5（或重新登录）以确保主题生效。

## 目录结构

```text
.
├── image/
│   └── macOS.png
└── macOS-dark/
	└── theme.conf
```

## 说明

- 主题配置文件位于 `macOS-dark/theme.conf`。
- 如需二次修改，可直接编辑该文件并重新加载 Fcitx5。
