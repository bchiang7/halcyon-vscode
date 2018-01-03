# Halcyon Theme for VS Code

[![Version](https://vsmarketplacebadge.apphb.com/version/brittanychiang.halcyon-vscode.svg)](https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode)
![Installs](https://vsmarketplacebadge.apphb.com/installs/brittanychiang.halcyon-vscode.svg)
![GitHub license](https://img.shields.io/github/license/bchiang7/halcyon-vscode.svg)

![demo](https://raw.githubusercontent.com/bchiang7/halcyon-vscode/master/images/demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
1. Search for `Halcyon`
1. Click **Install** to install it
1. Click **Reload** to reload the your editor
1. Code > Preferences > Color Theme > **Halcyon**
1. Code > Preferences > File Icon Theme > **Halcyon**

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://github.com/bchiang7/halcyon-vscode/blob/master/vsc-extension-quickstart.md)

## Colors

![colors](https://raw.githubusercontent.com/bchiang7/halcyon-vscode/master/images/colors.png)

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
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.fontFamily": "Fira Mono for Powerline",
  "terminal.integrated.fontSize": 12,
  "terminal.integrated.shell.osx": "zsh",
  "terminal.integrated.lineHeight": 1,
  "window.zoomLevel": 0.5,
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
  "macros": {
    "splitPane": [
      "workbench.action.splitEditor",
      "workbench.action.files.newUntitledFile",
      "workbench.action.moveEditorLeftInGroup",
      "workbench.action.closeEditorsToTheRight"
    ]
  },
  "powermode.enabled": false
}
```

## Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

Syntax & Workbench colors based on [Ayu Mirage Theme](https://github.com/teabyii/vscode-ayu)

File Icons based on [VS Code Great Icons](https://github.com/EmmanuelBeziat/vscode-great-icons)
