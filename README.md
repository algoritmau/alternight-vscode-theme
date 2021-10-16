# AlterNight 🌠

[![Version](https://vsmarketplacebadge.apphb.com/version/spaceinvadev.alternight.svg)](https://marketplace.visualstudio.com/items?itemName=spaceinvadev.alternight)
[![Downloads](https://img.shields.io/vscode-marketplace/r/spaceinvadev.alternight.svg)](https://marketplace.visualstudio.com/items?itemName=spaceinvadev.alternight)

A Visual Studio Code theme for those who code at night

<br />

## Previews

![Home Screen](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/images/preview-sidebar.png)

<br />

### ReactJS

![Preview JavaScript](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/images/preview-react.png)

<br />

### JavaScript

![Preview JavaScript](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/images/preview-javascript.png)

<br />

### HTML

![Preview HTML](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/images/preview-html.png)

<br />

### Sass

![Preview CSS](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/images/preview-sass.png)

<br />

### CSS

![Preview CSS](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/images/preview-css.png)

<br />

### JSON

![Preview JSON](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/images/preview-json.png)

<br />

## Installation

1. Open the **Extensions** sidebar panel in VS Code. `View → Extensions`

2. Search for `AlterNight`

3. Click `Install`

4. When prompted, select `AlterNight` as the color theme

> In case of not being prompted to select a Color Theme upon installing, go to the menu bar and select: `Code (File, on Windows) > Preferences > Color Theme > AlterNight`. Alternatively, you can use the shortcut `⌘/Ctrl + K > ⌘/Ctrl + T` and select `AlterNight`.

<br />

### Recommended settings for a better experience

The typeface shown in the screenshots is **MD IO** — a nice monospace font I really like. You can get it from [Future Fonts](https://www.futurefonts.xyz/mass-driver/io). I've also added some preferred typography-related settings, which you can get by adding the following to your `settings.json` file.

```json
// Controls the font family
"editor.fontFamily": "'MD IO 0.3', monospace",

// Controls the font size in pixels
"editor.fontSize": 18,

// Controls letter spacing in pixels
"editor.letterSpacing": -0.72,

// Controls the font weight
"editor.fontWeight": "400",

// Controls the line height. Use 0 to compute the line height from the font size
"editor.lineHeight": 34,

// Enables/Disables font ligatures
"editor.fontLigatures": true,
```

<br />

### Customize/Override theme colors

You can customize/override the AlterNight theme colors by adding the following theme-specific configuration to your settings file. For more advanced customization, refer to the corresponding [VS Code Docs](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

<br />

#### Example of basic customization

```json
"editor.tokenColorCustomizations": {
  "[AlterNight]": {
      "comments": "#229977"
  }
},
```

<br />

#### Example of advanced customization

```json
"editor.tokenColorCustomizations": {
  "[Your_Custom_AlterNight]": {
    "textMateRules": [
      {
        "scope": [
          "punctuation.definition.comment",
          "comment.block",
          "comment.line",
          "comment.block.documentation"
        ],
        "settings": {
          "foreground": "#ffff00"
        }
      }
    ]
  },
},

"workbench.colorCustomizations": {
  "[Your_Custom_AlterNight]": {
    "sideBar.background": "#ffff00",
  }
},
```

<br />

### Contributions, Issues & Suggestions

Any feedback, issue reporting or suggestion is welcome. Feel free to submit your concern via the [Repo's GitHub Issues](https://github.com/spaceinvadev/alternight-vscode-theme/issues) page, provide feedback or request a feature by submitting a PR.

<br />

### Changelog

All notable changes to this project are documented in the [changelog](CHANGELOG.md). Consider checking the changelog prior to filing any issues as they may have already been addressed.

<br />

## Credits

Made with ❤️ by [@spaceinvadev](https://twitter.com/spaceinvadev)
