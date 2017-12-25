# Halcyon Theme for VS Code

![demo](https://raw.githubusercontent.com/bchiang7/halcyon-vscode/master/images/demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
1. Search for `Halcyon`
1. Click **Install** to install it.
1. Click **Reload** to reload the your editor
1. Code > Preferences > Color Theme > **Halcyon**
1. Code > Preferences > File Icon Theme > **Halcyon**
1. Optional: Use the recommended settings below for best experience

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://github.com/bchiang7/halcyon-vscode/blob/master/vsc-extension-quickstart.md)

## Main Colors

### Workbench

* Background: `#191e27`
* Editor Background: `#212733`
* Grey: `#738699`
* Accent Yellow: `#ffcc66`
* White: `#d9d7ce`

### Syntax

* Blue: `#5ccfe6`
* Green: `#bae67e`
* Orange: `#ffae57`
* Yellow: `#ffd580`
* Purple: `#c3a6ff`
* Red: `#f07178`
* Grey: `#abb2bf`
* Dark Grey: `#607080`
* Seafoam: `#95e6cb`
* Magenta: `#c678dd`

## Recommended Settings (Used with a 2017 Macbook Pro)

[Download Inconsolata Font](https://fonts.google.com/specimen/Inconsolata)

```json
{
  "eslint.autoFixOnSave": true,
  "editor.colorDecorators": false,
  "editor.detectIndentation": true,
  "editor.fontSize": 14,
  "editor.fontFamily": "Inconsolata",
  "editor.fontLigatures": true,
  "editor.formatOnPaste": false,
  "editor.insertSpaces": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.renderWhitespace": "none",
  "editor.snippetSuggestions": "top",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "files.trimFinalNewlines": true,
  "sublimeTextKeymap.promptV3Features": true,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.lineHeight": 1.25,
  "workbench.iconTheme": "Halcyon",
  "workbench.colorTheme": "Halcyon",
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.startupEditor": "newUntitledFile",
  "files.exclude": {
    "node_modules/": true,
    "tmp/": true
  },
  "search.exclude": {
    "node_modules/": true,
    "dist/": true,
    "tmp/": true
  },
  "window.zoomLevel": 0.5
}
```

## Reference

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

Syntax & Workbench colors based on [Ayu Mirage Theme](https://github.com/teabyii/vscode-ayu)

File Icons based on [VS Code Great Icons](https://github.com/EmmanuelBeziat/vscode-great-icons)
