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
    <img alt="Version" src="https://img.shields.io/visual-studio-marketplace/v/brittanychiang.halcyon-vscode?color=brightgreen" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Downloads" src="https://img.shields.io/visual-studio-marketplace/d/brittanychiang.halcyon-vscode" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Installs" src="https://img.shields.io/visual-studio-marketplace/i/brittanychiang.halcyon-vscode" />
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

|                                 Color                                  | Usage                                           |
| :--------------------------------------------------------------------: | ----------------------------------------------- |
| ![#c3a6ff](https://placehold.co/1x1/c3a6ff/c3a6ff.png) `#c3a6ff` | Keywords, constants, template literals          |
| ![#ffd580](https://placehold.co/1x1/ffd580/ffd580.png) `#ffd580` | Functions, classes, object literal keys         |
| ![#ffae57](https://placehold.co/1x1/ffae57/ffae57.png) `#ffae57` | Constants, operators                            |
| ![#bae67e](https://placehold.co/1x1/bae67e/bae67e.png) `#bae67e` | Strings, markdown headings                      |
| ![#5ccfe6](https://placehold.co/1x1/5ccfe6/5ccfe6.png) `#5ccfe6` | Special keywords, classes, markdown code blocks |
| ![#a2aabc](https://placehold.co/1x1/a2aabc/a2aabc.png) `#a2aabc` | Variables, property names, tags                 |

### UI Colors

|                                 Color                                  | Usage                                      |
| :--------------------------------------------------------------------: | ------------------------------------------ |
| ![#171c28](https://placehold.co/1x1/171c28/171c28.png) `#171c28` | Workbench background                       |
| ![#1d2433](https://placehold.co/1x1/1d2433/1d2433.png) `#1d2433` | Editor background                          |
| ![#2f3b54](https://placehold.co/1x1/2f3b54/2f3b54.png) `#2f3b54` | Highlight, widgets, panels                 |
| ![#6679a4](https://placehold.co/1x1/6679a4/6679a4.png) `#6679a4` | Dividers, subtle UI elements               |
| ![#8695b7](https://placehold.co/1x1/8695b7/8695b7.png) `#8695b7` | Status bar text, buttons, etc              |
| ![#d7dce2](https://placehold.co/1x1/d7dce2/d7dce2.png) `#d7dce2` | Active text, anything that should be white |
| ![#ffcc66](https://placehold.co/1x1/ffcc66/ffcc66.png) `#ffcc66` | Accent, list tree titles, badges, etc      |
| ![#bae67e](https://placehold.co/1x1/bae67e/bae67e.png) `#bae67e` | Addition highlights                        |
| ![#ef6b73](https://placehold.co/1x1/ef6b73/ef6b73.png) `#ef6b73` | Deletion highlights, errors, warnings      |
| ![#5ccfe6](https://placehold.co/1x1/5ccfe6/5ccfe6.png) `#5ccfe6` | Modified highlights                        |

## Theming Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

Syntax & Workbench colors based on [Ayu Mirage Theme](https://github.com/teabyii/vscode-ayu)

```bash
vsce publish patch/minor/major
```

Publish to Open VSX (Cursor)

```bash
ovsx publish
```

## Shameless Plug

Halcyon is also available for [Sublime Text, Atom, iTerm, and more!](https://halcyon-theme.netlify.app/).
