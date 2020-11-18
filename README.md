# Purpura

[![Version](https://vsmarketplacebadge.apphb.com/version/spaceinvadev.purpura.svg)](https://aka.ms/purpura)
[![Downloads](https://img.shields.io/vscode-marketplace/r/spaceinvadev.purpura.svg)](https://aka.ms/spaceinvadev)

A Visual Studio Code theme for purple lovers

## Purpura

![Home Screen](home-screen.jpg)
![Purpura Frameworks](three-dark.jpg)

## Purpura Light

![Home Screen (Light)](light-owl-full.jpg)
![Purpura Light Frameworks](three-light.jpg)

## Installation

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Launch Visual Studio Code
3. Choose **Extensions** from menu
4. Search for `Purpura`
5. Click **Install** to install it
6. Click **Reload** to reload the Code
7. From the menu bar click: Code > Preferences > Color Theme > **Purpura**

### Separate the Editor from the Sidebar

This theme uses contrast sparingly so that when it's applied, it's more meaningful. This can help reduce noise and improve your ability to scan. However, some of the decisions may not work for everyone. One such decision that some disagree on is whether or not to have a separation between the editor and sidebar, and the amount of contrast. If you wish for this to have more visual significance, please paste this into your user settings preferences. These are my recommendations for these settings but you can use whatever colors you wish.

```json
"workbench.colorCustomizations": {
  "[Purpura]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  },
  "[Purpura Light]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  }
},
```

### Preferences shown in the preview

The font in the preview image is _CodeNewRoman NF_, a nerd font you can download from the [Nerd Fonts](https://www.nerdfonts.com/) wesbite. To enable ligatures on the editor, add the below settings to your `settings.json` file:

```json
"editor.fontFamily": "CodeNewRoman NF",
"editor.fontLigatures": true,
```

The preview image is using [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer), a really cool extension that highlights matching brackets. This can help reduce unwanted errors.

I use this setting:

```json
"bracketPairColorizer.forceIterationColorCycle": true,
```

![Bracket](bracket.png)

## Contribution and Changelog

This is my first time creating a theme, so chances are that I did something wrong or I missed something. Ih that's the case, feel free to [file an issue](https://github.com/spaceinvadev/purpura-vscode-theme/issues), provide feedback or request a feature by submitting a PR.

All relevant changes for each version are outlined in the changelog. Consider updating and checking the changelog before filing any issues, as they may have already been addressed.
