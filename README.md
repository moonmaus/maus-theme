# Maus Theme

[![Version](https://vsmarketplacebadges.dev/version/moonmaus.maus-theme.svg?&colorB=orange)](https://marketplace.visualstudio.com/items?itemName=moonmaus.maus-theme)
![GitHub](https://img.shields.io/github/license/moonmaus/maus-theme?&colorB=blue)


<!-- ![GitHub package.json version](https://img.shields.io/github/package-json/v/moonmaus/maus-theme) -->
<!-- ![GitHub release (latest by date)](https://img.shields.io/github/v/release/moonmaus/maus-theme?logo=github) -->
<!-- ![Visual Studio Marketplace Version](https://marketplace.visualstudio.com/items?itemName=moonmaus.maus-theme) -->

<p align="left">
    <img src="https://raw.githubusercontent.com/moonmaus/maus-theme/main/assets/maus-dark-icon.png" width="160" alt="Maus Theme icon">
</p>

> A vibrant dark theme for [Visual Studio Code](http://code.visualstudio.com) that adapts to reduced screen brightness, providing enhanced readability.
<p align="left">
    <img src="https://raw.githubusercontent.com/moonmaus/maus-theme/main/assets/maus-dark-screen.png" width="800" alt="Maus Theme screenshot">
</p>

## Syntax Highlighting

Basic syntax highlighting is available for most languages. Levels of refinement to-date are shown below:

| Language     | Refinement | Updates            |
|--------------|------------|--------------------|
| `Go`         | High       |                    |
| `TypeScript` | High       |                    |
| `JavaScript` | High       |                    |
| `JSON`       | Moderate   | Planned (`v0.0.8`) |
| `Lua`        | Moderate   |                    |
| `CSS`        | Moderate   |                    |
| `Markdown`   | Moderate   |                    |
| `Unix Shell` | Low        |                    |
| `Python`     | Low        | Planned (`v0.0.8`) |

## Features

| Feature                    | Description                                                       |
|----------------------------|-------------------------------------------------------------------|
| **Optimized Dark Mode**    | Deep, low-light background paired with a balanced vibrant palette |
| **Refined Highlighting**   | Distinct hues for functions, operators, constants, and strings    |
| **Reduced Visual Fatigue** | Subtly desaturated accents help ease long coding sessions         |
| **Refined IDE Scheme**     | Seamless interface contrast to elevate the editor                 |

## Install

In a VS Code instance:

1. Open the Command Palette (`ctrl + P` or `cmd + P`)
2. Type `ext install maus` and press `enter / return`
3. Click 'Install' button under **`Maus Theme`**

## Set Dark Theme

Edit `settings.json`:

1. Open the Editor Command Palette (`ctrl + shift + P` or `cmd + shift +  P`)
2. Type `Open User Settings (JSON)` and press `enter / return`
3. Add the following:

```json
    "workbench.colorTheme": "Maus Dark",
    "workbench.preferredDarkColorTheme": "Maus Dark",
```

## Optional Settings

Here are some of my preferred settings:

```json
    "editor.fontFamily": "Berkeley Mono",
    "editor.fontSize": 13,
    "debug.console.fontSize": 13,
    "terminal.integrated.fontSize": 13,
    "editor.wordWrap": "on",     
    "editor.wordWrapColumn": 96,
    "editor.hover.delay": 1000,
    "editor.hover.hidingDelay": 100,
    "editor.cursorStyle": "block",
```

Additionally, here are my colors for the **[Indent Rainbow](https://github.com/oderwat/vscode-indent-rainbow)** extension:

```json
    "editor.guides.indentation": true,
    "indentRainbow.colors": [
        "rgba(53, 52, 53,0.15)",
        "rgba(42, 51, 136,0.15)",
        "rgba(94, 45, 144, 0.15)",
        "rgba(123, 28, 125,0.15)",
        "rgba(218, 18, 75,0.15)",
        "rgba(239, 83, 61,0.15)",
        "rgba(246, 140, 31,0.15)",
        "rgba(246, 140, 31,0.1)",
        "rgba(246, 140, 31,0.05)",
        "rgba(246, 140, 31,0.025)"
    ],
```

## Contributing

If you'd like to improve **`Maus Theme`** or report an [issue](https://github.com/moonmaus/maus-theme/issues), please open a [pull request](https://github.com/moonmaus/maus-theme/pulls) or an issue on GitHub.

## License

**`Maus Theme`** is released under the [MIT License](./LICENSE).