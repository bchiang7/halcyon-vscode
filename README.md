<p align="center">
  <img alt="Halcyon Logo" src="https://raw.githubusercontent.com/bchiang7/halcyon-vscode/master/images/logo.png" width="100" />
</p>
<h1 align="center">
  Halcyon Theme for VS Code
</h1>
<p align="center">
  A minimal, dark blue theme for <a href="https://halcyon-theme.netlify.com/">VS Code, Sublime Text, Atom, and more</a>.
</p>
<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Version" src="https://vsmarketplacebadge.apphb.com/version/brittanychiang.halcyon-vscode.svg" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Downloads" src="https://vsmarketplacebadge.apphb.com/downloads/brittanychiang.halcyon-vscode.svg" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Installs" src="https://vsmarketplacebadge.apphb.com/installs/brittanychiang.halcyon-vscode.svg" />
  </a>
</p>

![demo](https://raw.githubusercontent.com/bchiang7/halcyon-vscode/master/images/demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Halcyon`
3. Click **Install** to install it
4. Click **Reload** to reload the editor
5. Code > Preferences > Color Theme > **Halcyon**

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://github.com/bchiang7/halcyon-vscode/blob/master/vsc-extension-quickstart.md)

## Icon Theme

The file icon theme seen in the screenshot above is [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) with these settings:

```json
  "material-icon-theme.folders.color": "#8695b7",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
```

## Color Reference

### Syntax Colors

|                               Color                                | Usage                                           |
| :----------------------------------------------------------------: | ----------------------------------------------- |
| ![#c3a6ff](https://via.placeholder.com/10/c3a6ff?text=+) `#c3a6ff` | Keywords, constants, template literals          |
| ![#ffd580](https://via.placeholder.com/10/ffd580?text=+) `#ffd580` | Functions, classes, object literal keys         |
| ![#ffae57](https://via.placeholder.com/10/ffae57?text=+) `#ffae57` | Constants, operators                            |
| ![#bae67e](https://via.placeholder.com/10/bae67e?text=+) `#bae67e` | Strings, markdown headings                      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6?text=+) `#5ccfe6` | Special keywords, classes, markdown code blocks |
| ![#a2aabc](https://via.placeholder.com/10/a2aabc?text=+) `#a2aabc` | Variables, property names, tags                 |

### UI Colors

|                               Color                                | Usage                                      |
| :----------------------------------------------------------------: | ------------------------------------------ |
| ![#171c28](https://via.placeholder.com/10/171c28?text=+) `#171c28` | Workbench background                       |
| ![#1d2433](https://via.placeholder.com/10/1d2433?text=+) `#1d2433` | Editor background                          |
| ![#2f3b54](https://via.placeholder.com/10/2f3b54?text=+) `#2f3b54` | Highlight, widgets, panels                 |
| ![#6679a4](https://via.placeholder.com/10/6679a4?text=+) `#6679a4` | Dividers, subtle UI elements               |
| ![#8695b7](https://via.placeholder.com/10/8695b7?text=+) `#8695b7` | Status bar text, buttons, etc              |
| ![#d7dce2](https://via.placeholder.com/10/d7dce2?text=+) `#d7dce2` | Active text, anything that should be white |
| ![#ffcc66](https://via.placeholder.com/10/ffcc66?text=+) `#ffcc66` | Accent, list tree titles, badges, etc      |
| ![#bae67e](https://via.placeholder.com/10/bae67e?text=+) `#bae67e` | Addition highlights                        |
| ![#ef6b73](https://via.placeholder.com/10/ef6b73?text=+) `#ef6b73` | Deletion highlights, errors, warnings      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6?text=+) `#5ccfe6` | Modified highlights                        |

## Theming Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

Syntax & Workbench colors based on [Ayu Mirage Theme](https://github.com/teabyii/vscode-ayu)

```bash
vsce publish patch/minor/major
```

## Shameless Plug

Halcyon is also available for [Sublime Text, Atom, iTerm, and more!](https://halcyon-theme.netlify.com/).
