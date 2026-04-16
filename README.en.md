# maclike-fcitx5-themes

[🇨🇳 中文](./READ.md) | [🇬🇧 English](./README.en.md)

A clean macOS-like theme for Fcitx5, suitable for general Fcitx5 usage (including common Fcitx5 Rime setups).

## Preview

![Theme Preview](./image/macOS.png)

## Requirements

- Fcitx5 is installed and enabled

## Installation

1. Clone this repository

```bash
git clone https://github.com/moyuwangzi/maclike-fcitx5-themes.git
cd maclike-fcitx5-themes
```

2. Copy the theme to your local Fcitx5 themes directory

```bash
mkdir -p ~/.local/share/fcitx5/themes
cp -r macOS-dark ~/.local/share/fcitx5/themes/
```

## Enable the Theme

1. Open the Fcitx5 configuration tool.
2. Go to Addons and find Classic User Interface.
3. Set the theme to `macOS-dark`.
4. Reload Fcitx5 (or re-login) to ensure the theme is applied.

## Project Structure

```text
.
├── image/
│   └── macOS.png
└── macOS-dark/
    └── theme.conf
```

## Notes

- Theme configuration is stored in `macOS-dark/theme.conf`.
- You can customize it directly and reload Fcitx5 to apply changes.
