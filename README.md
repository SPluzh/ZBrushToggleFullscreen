# ToggleFullscreen — ZBrush Plugin

A ZBrush plugin that toggles a clean fullscreen view by hiding UI elements,
and fits the canvas to window size.

---

## Features

- **Fullscreen toggle** — hide/show selected UI elements with one hotkey
- **Fit Canvas** — resize canvas to fit current window
- Configurable — choose which elements to hide
- Settings are saved between sessions

---

## Installation

1. Copy `ToggleFullscreen.zsc` and `ToggleFullscreenData/` folder to:
```
ZBrush/ZStartup/ZPlugs64/
```
2. Restart ZBrush
3. Plugin appears in **ZPlugin → ToggleFullscreen**

## File Structure
```
ZStartup/ZPlugs64/
├── ToggleFullscreen.zsc
└── ToggleFullscreenData/
      └── FullscreenSettings.zvr (auto-created)
```

---

## Usage

### Fullscreen

Press `F11` to toggle fullscreen view.  
All selected UI elements will be hidden/restored.

### Fit Canvas

Press `Ctrl+F11` to fit canvas to current window size.

---

## Hotkeys

| Hotkey | Action |
|--------|--------|
| `F11` | Toggle Fullscreen |
| `Ctrl+F11` | Fit Canvas to Window |

---

## Fullscreen Settings

**ZPlugin → ToggleFullscreen → Fullscreen Settings**

Configure what gets hidden when entering fullscreen:

| Option | Description |
|--------|-------------|
| Hide Menus | Top menu bar |
| Hide Title | ZBrush title bar |
| Hide Notes | Top-left notes area |
| Hide Bottom | Bottom tray edge |
| Hide History | Undo History selector |
| Hide Palettes | Floating palettes (same as Tab) |
| Hide Left Tray | Collapse left tray |
| Hide Right Tray | Collapse right tray |
> ⚠️ **Hide Left Tray / Hide Right Tray** — collapsing trays may cause
> brief UI flickering during transition. This is expected behavior.

---

## Fit Canvas Settings

**ZPlugin → ToggleFullscreen → FitCanvas Settings**

| Option | Description |
|--------|-------------|
| Disable Pro (Proportional) | Disables proportional constraint when resizing canvas |

---
## License

MIT
