# 🌙 Tomorrow Chat Blue
> A ChatGPT App theme inspired by the Tomorrow Night Blue color scheme.

<!-- ![Preview](../assets/previews/tomorrow-chat-blue.png) -->
<p align="center">
    <img src="../assets/previews/tomorrow-chat-blue.png" width="800">
</p>

## Theme

Copy and paste the following configuration:

```json
codex-theme-v1: {
    "codeThemeId": "codex",
    "theme": {
        "accent": "#0f9fff",
        "accentSource": "custom",
        "contrast": 60,
        "fonts": {
            "code": null,
            "ui": "\"JetBrainsMono Nerd Font\""
        },
        "ink": "#dbff9c",
        "opaqueWindows": false,
        "semanticColors": {
            "diffAdded": "#40c977",
            "diffRemoved": "#fa423e",
            "skill": "#ad7bf9"
        },
        "surface": "#002451"
    },
    "variant": "dark"
}
```

## Colors

| Property | Color | Value |
|---|---|---|
| Surface | 🔵 Deep Blue | `#002451` |
| Accent | 🔵 Bright Blue | `#0f9fff` |
| Text / Ink | 🟢 Light Lime | `#dbff9c` |
| Diff Added | 🟢 Green | `#40c977` |
| Diff Removed | 🔴 Red | `#fa423e` |
| Skill | 🟣 Purple | `#ad7bf9` |

## Notes

- Designed for dark-mode applications.
- Inspired by the **Tomorrow Night Blue** color scheme.
- Uses a deep blue surface with bright blue accents and light lime text.
- Uses **JetBrainsMono Nerd Font** for the UI.
- Window transparency is enabled because `opaqueWindows` is set to `false`.
- Added and removed diff states use green and red respectively for clear code-change visibility.
- Skill-related elements use purple as their semantic color.