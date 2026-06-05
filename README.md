# pi-catppuccin

[Catppuccin](https://github.com/catppuccin/catppuccin) themes for the [pi](https://github.com/earendil-works/pi) coding agent.

## Flavors

| Flavor | Theme Name | Type |
|--------|-----------|------|
| 🌻 Latte | `catppuccin-latte` | Light |
| 🪴 Frappé | `catppuccin-frappe` | Dark |
| 🌺 Macchiato | `catppuccin-macchiato` | Dark |
| 🌿 Mocha | `catppuccin-mocha` | Dark |

## Install

```bash
bun add -g pi-catppuccin
```

Or with npm:

```bash
npm install -g pi-catppuccin
```

## Usage

Select a theme via `/settings` in pi, or edit `~/.pi/agent/settings.json`:

```json
{
  "theme": "catppuccin-mocha"
}
```

### Available themes

- `catppuccin-latte` — Light theme
- `catppuccin-frappe` — Medium dark theme
- `catppuccin-macchiato` — Dark theme
- `catppuccin-mocha` — Darkest theme

## Color Mapping

Catppuccin colors are mapped to pi tokens as follows:

| Pi Token | Catppuccin Color |
|----------|-----------------|
| `accent` | Mauve |
| `success` | Green |
| `error` | Red |
| `warning` | Yellow |
| `syntaxKeyword` | Mauve |
| `syntaxFunction` | Blue |
| `syntaxVariable` | Yellow |
| `syntaxString` | Green |
| `mdHeading` | Peach |

## License

MIT — Catppuccin colors are MIT licensed.
