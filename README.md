# Maus Theme

<p align="left">
    <img src="https://raw.githubusercontent.com/moonmaus/maus-theme/main/assets/maus-dark-icon.png" width="160" alt="Maus Theme icon">
</p>

> A vibrant dark theme for [Visual Studio Code](http://code.visualstudio.com) designed to enhance readability when screen brightness is reduced.
<p align="left">
    <img src="https://raw.githubusercontent.com/moonmaus/maus-theme/main/assets/maus-dark-screen.png" width="800" alt="Maus Theme screenshot">
</p>


## Syntax Highlighting

Basic syntax highlighting is available for most languages, but version `v0.0.2` introduces initial refinements for:

- Go
- TypeScript / JavaScript
- JSON
- Markdown

Planned enhancements in version `v0.0.4` include:

- Shell
- CSS
- Python

## Features

- **Optimized Dark Mode:** Uses a deep, low-light background paired with a balanced color palette.
- **Refined Syntax Highlighting:** Distinct hues for functions, operators, constants, and strings create clear visual groupings.
- **Reduced Visual Fatigue:** Vivid accents have been subtly desaturated to ease long coding sessions.

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

## Contributing

If you'd like to improve **`Maus Theme`** or report an [issue](https://github.com/moonmaus/maus-theme/issues), please open a [pull request](https://github.com/moonmaus/maus-theme/pulls) or an issue on GitHub.

## License

**`Maus Theme`** is released under the [MIT License](./LICENSE).