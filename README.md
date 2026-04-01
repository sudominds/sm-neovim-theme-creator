# Neovim Theme Creator

A browser-based tool for designing custom Neovim colorschemes with a live preview. No installs, no build step — just open and create.

**[Live Demo →](https://sudominds.github.io/sm-neovim-theme-creator/)**

---

## What it does

You get a simulated Neovim editor that updates in real time as you tweak colors. When you're happy with the result, export it directly to a file you can drop into your Neovim config.

![screenshot placeholder](screenshot.png)

---

## Features

- **Live preview** — see your theme applied to real code as you edit
- **3 built-in presets** to start from — Catppuccin, Gruvbox, TokyoNight
- **37 customizable color variables** organized into logical groups:
  - Editor UI (background, foreground, cursor line, line numbers, selection, borders)
  - Tabline
  - Statusline + per-mode colors (Normal, Insert, Visual, Command, Terminal)
  - Syntax highlighting (keywords, strings, functions, types, comments, and more)
  - Popup / floating windows
  - Diagnostics (errors, warnings, info, hints)
- **3 color input methods** — color picker, hex value, or HSL sliders
- **Toggle Vim modes** in the preview to check how your statusline colors look
- **Switch syntax languages** in the preview (Lua, Python, JavaScript)
- **Export in 3 formats:**

  | Format          | File location                                   |
  | --------------- | ----------------------------------------------- |
  | Lua colorscheme | `~/.config/nvim/colors/mytheme.lua`             |
  | Lualine theme   | `~/.config/nvim/lua/lualine/themes/mytheme.lua` |
  | VimScript       | `~/.config/nvim/colors/mytheme.vim`             |

---

## How to use

1. Pick a preset or start tweaking colors from scratch
2. Use the right-hand panel to adjust any color — click a swatch to open the picker, or type a hex value directly
3. Watch the preview update live; toggle modes and languages to stress-test your palette
4. Hit **Export**, choose your format, and copy to clipboard
5. Paste the output into the suggested file path in your Neovim config

---

## Run locally

No dependencies — just open the file:

```bash
open index.html
# or
python -m http.server
```
