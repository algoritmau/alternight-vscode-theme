# AlterNight 🌠

[![Version](https://vsmarketplacebadge.apphb.com/version/spaceinvadev.alternight.svg)](https://marketplace.visualstudio.com/items?itemName=spaceinvadev.alternight)
[![Downloads](https://img.shields.io/vscode-marketplace/r/spaceinvadev.alternight.svg)](https://marketplace.visualstudio.com/items?itemName=spaceinvadev.alternight)

A Visual Studio Code theme for those who code at night

## AlterNight

![Home Screen](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/preview-sidebar.png)

### JavaScript

![Preview JavaScript](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/preview-javascript.png)

### HTML

![Preview HTML](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/preview-html.png)

### CSS

![Preview CSS](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/preview-css.png)

### JSON

![Preview JSON](https://raw.githubusercontent.com/spaceinvadev/alternight-vscode-theme/main/preview-json.png)

## Installation

1. Open the **Extensions** sidebar panel in VS Code. `View → Extensions`

2. Search for `AlterNight`

3. Click `Install`

4. When prompted, select `AlterNight` as the color theme

> In case of not being prompted to select a Color Theme upon installing, go to the menu bar and select: `Code (File, on Windows) > Preferences > Color Theme > AlterNight`. Alternatively, you can use the shortcut `⌘/Ctrl + K > ⌘/Ctrl + T` and select `AlterNight`.

### Recommended settings for a better experience

The typeface I used (as shown on the sample images) is **MonoLisa** — a nice coding font I really like. You can get it at [MonoLisa](https://monolisa.dev/). I've added some personal typography-related settings, which you can achieve by adding the following to your `settings.json` file.

```json
// Controls the font family
"editor.fontFamily": "'MonoLisa', monospace",

// Controls the font size in pixels
"editor.fontSize": 17,

// Controls letter spacing in pixels
"editor.letterSpacing": -0.4,

// Controls the font weight
"editor.fontWeight": "300",

// Controls the line height. Use 0 to compute the line height from the font size
"editor.lineHeight": 40,

// Enables/Disables font ligatures
"editor.fontLigatures": true,
```

### Customize/Override theme colors

You can customize/override the AlterNight theme colors by adding the following theme-specific configuration to your settings file. For more advanced customization, refer to the corresponding [VS Code Docs](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

#### Example of basic customization

```json
"editor.tokenColorCustomizations": {
    "[AlterNight]": {
        "comments": "#229977"
    }
},
```

#### Example of advanced customization

```json
"editor.tokenColorCustomizations": {
    "[AlterNight YOUR_REMIX]": {
        "textMateRules": [
            {
                "scope": [
                    "punctuation.definition.comment",
                    "comment.block",
                    "comment.line",
                    "comment.block.documentation"
                ],
                "settings": {
                    "foreground": "#FFFF00"
                }
            }
        ]
    },
},

"workbench.colorCustomizations": {
	"[AlterNight YOUR_REMIX]": {
		"sideBar.background": "#FFFF00",
	}
},
```

### Contributions, Issues & Suggestions

Any feedback, issue reporting or suggestion is welcome. Feel free to submit your concern via the [Repo's GitHub Issues](https://github.com/spaceinvadev/alternight-vscode-theme/issues) page, provide feedback or request a feature by submitting a PR.

### Changelog

All notable changes to this project are documented in the [changelog](CHANGELOG.md). Consider checking the changelog prior to filing any issues as they may have already been addressed.
