# vscode shields.io snippets

[![vsm-version](https://img.shields.io/visual-studio-marketplace/v/relliv.shieldsio-snippets?style=flat&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=relliv.shieldsio-snippets)
[![license](https://img.shields.io/github/license/relliv/vscode-shieldsio-snippets?style=flat&color=lightgrey)](https://github.com/relliv/vscode-shieldsio-snippets/blob/master/LICENSE)

shields.io snippets for markdown documents.

> [!WARNING]  
> This repository forked from [alexzshl/vscode-badges-snippets](https://github.com/relliv/vscode-shieldsio-snippets/tree/dev) and **it is not official shields.io extension.**

## Preview

### Icon badge generation
![preview](./images/preview_generic-badge-generation.gif)

### Github badge generation
![preview](./images/preview_github-badge-example.gif)


### Bulk badge generation

![preview](./images/preview_github-bulk-badge-generation.gif)

## Features

- Static badge with list of color/style/logo
- Quick and easy service support
- Quickly generate badges using clipboard data

## Extension Settings

If the snippets for markdown doesn't work, please add the following settings in settings.json:

```json
  "[markdown]": {
    "editor.quickSuggestions": {
      "other": true,
      "comments": true,
      "strings": true,
    }
  }
```

## Usages

Enter the full name or shorthand for the code snippet item, select and press the tab key. Next you need to fill in the placeholders in order.

- `badge static` or `bs` - Create static badge
- `badge vsm version` - Create dynamic badge for an extension on Visual Studio Marketplace
- `badge github stars` - Create dynamic badge for stars of a repository on Github

## Release Notes

### 0.0.2

- Added bulk Github repo snippets
- Added NPM download and bundle size snippets

### 0.0.1

- Initial release