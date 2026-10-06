# ☀️ Solarized Chat

> A ChatGPT App theme inspired by the Solarized Light color scheme.

<p align="center">
    <img src="../assets/previews/solarized-chat.png" width="800">
</p>

```json
codex-theme-v1: {
    "codeThemeId": "codex",
    "theme": {
        "accent": "#859a07",
        "accentSource": "custom",
        "contrast": 90,
        "fonts": {
            "code": null,
            "ui": "\"JetBrainsMono Nerd Font\""
        },
        "ink": "#cb4b37",
        "opaqueWindows": false,
        "semanticColors": {
            "diffAdded": "#00a240",
            "diffRemoved": "#e02e2a",
            "skill": "#b06dff"
        },
        "surface": "#fdf6e3"
    },
    "variant": "light"
}
```

## Colors

| Property | Color | Value |
|---|---|---|
| Surface | 🟡 Warm Cream | `#fdf6e3` |
| Accent | 🟢 Olive Green | `#859a07` |
| Text / Ink | 🔴 Burnt Orange | `#cb4b37` |
| Diff Added | 🟢 Green | `#00a240` |
| Diff Removed | 🔴 Red | `#e02e2a` |
| Skill | 🟣 Purple | `#b06dff` |

## Notes

- Designed for light-mode applications.
- Inspired by the **Solarized Light** color scheme.
- Uses a warm cream surface to reduce the harshness of a pure white interface.
- Uses olive green accents with burnt orange text for a warm, distinctive appearance.
- Uses **JetBrainsMono Nerd Font** for the UI.
- Window transparency is enabled because `opaqueWindows` is set to `false`.
- Added and removed diff states use green and red respectively for clear code-change visibility.
- Skill-related elements use purple as their semantic color.