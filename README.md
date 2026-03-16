# ゆったり

**yuttari** /jɯttaɾi/ — a calm, relaxed palette 〜 soft hues that feel like a quiet afternoon.

> for years, i've been painting every screen i touch with these colors — my terminal, my website, slack, even my phone. it's the palette that makes everything feel a little softer, a little quieter. now it's yours too.
>
> *– [ramses c.](https://ramses.work)*

🌸 **[View the showcase →](https://ramsescab.github.io/bloomcolors/)**

---

## Colors

### ☀ Light

| Color | Hex | Description |
|-------|-----|-------------|
| Background | `#ffedf4` | Soft pink-lavender |
| Foreground | `#4a3c42` | Dark muted brown-purple |
| Red | `#b85e5e` | Muted rose |
| Green | `#7a9b7a` | Soft sage green |
| Blue | `#7a8bb8` | Dusty blue |
| Yellow | `#c2a875` | Warm cream |
| Magenta | `#a67ba6` | Soft mauve |
| Cyan | `#7bb8b8` | Muted teal |
| Bright Red | `#d47979` | Warmer rose |
| Bright Green | `#8fb58f` | Brighter sage |
| Bright Blue | `#8fa5d4` | Lighter dusty blue |
| Bright Yellow | `#ddc299` | Lighter cream |
| Bright Magenta | `#c299c2` | Brighter mauve |
| Bright Cyan | `#99d4d4` | Lighter teal |

### ☾ Dark

| Color | Hex | Description |
|-------|-----|-------------|
| Background | `#1e181c` | Deep muted plum |
| Foreground | `#ffedf4` | Soft pink-lavender |
| Red | `#c06868` | Muted rose |
| Green | `#82a682` | Soft sage green |
| Blue | `#8494c0` | Dusty blue |
| Yellow | `#ccb07e` | Warm cream |
| Magenta | `#b085b0` | Soft mauve |
| Cyan | `#82c0c0` | Muted teal |
| Bright Red | `#e08a8a` | Warmer rose |
| Bright Green | `#9cc49c` | Brighter sage |
| Bright Blue | `#a0b4de` | Lighter dusty blue |
| Bright Yellow | `#e6cda6` | Lighter cream |
| Bright Magenta | `#cda6cd` | Brighter mauve |
| Bright Cyan | `#a6dede` | Lighter teal |

---

## Usage

The [showcase site](https://ramsescab.github.io/bloomcolors/) includes a built-in **Export** section with copy-paste configs for:

| Format | Where to paste |
|--------|----------------|
| **Raw** | Plain key/value pairs |
| **CSS** | `:root` custom properties |
| **VS Code** | `settings.json` color theme |
| **iTerm2** | Color preset (plist XML) |
| **Windows Terminal** | `settings.json → schemes[]` |
| **Alacritty** | `alacritty.toml` |
| **Slack** | Preferences → Themes → Custom Theme |

### Quick start — CSS

```css
:root {
  --bg: #ffedf4;
  --fg: #4a3c42;
  --red: #b85e5e;
  --green: #7a9b7a;
  --blue: #7a8bb8;
  --yellow: #c2a875;
  --magenta: #a67ba6;
  --cyan: #7bb8b8;
  --red-bright: #d47979;
  --green-bright: #8fb58f;
  --blue-bright: #8fa5d4;
  --yellow-bright: #ddc299;
  --magenta-bright: #c299c2;
  --cyan-bright: #99d4d4;
}
```

### Quick start — Alacritty

```toml
# ゆったり Light — ~/.config/alacritty/alacritty.toml

[colors.primary]
background = "#ffedf4"
foreground = "#4a3c42"

[colors.normal]
red = "#b85e5e"
green = "#7a9b7a"
blue = "#7a8bb8"
yellow = "#c2a875"
magenta = "#a67ba6"
cyan = "#7bb8b8"

[colors.bright]
red = "#d47979"
green = "#8fb58f"
blue = "#8fa5d4"
yellow = "#ddc299"
magenta = "#c299c2"
cyan = "#99d4d4"
```

---

## About this repo

This is a single `index.html` file — no build tools, no dependencies. Just open it in a browser.

```bash
# clone and open
git clone https://github.com/ramsescab/bloomcolors.git
open bloomcolors/index.html
```

The showcase includes:
- **Color swatches** — cards, list, and grid views
- **Terminal preview** — syntax-highlighted Python
- **Syntax preview** — JavaScript, HTML/CSS, Python, Rust
- **UI preview** — buttons, badges, inputs, alerts, status indicators
- **Banner preview** — visual poster with gradient background
- **Export** — 7 copy-paste formats with light/dark toggle

---

## Credits

Designed by [@ramsescab](https://github.com/ramsescab) · Fine tuned with [rampa](https://github.com/basiclines/rampa) by [@basiclines](https://github.com/basiclines)

---

## License

MIT
