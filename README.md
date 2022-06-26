# Aurelia HTML Syntax for Sublime Text

based on the official sublime html syntax

*Please note the plugin hasn't been submitted to [packagecontrol.io](https://packagecontrol.io/). Thus has to be installed manually.*

## Installation

- Install `Aurelia HTML`
    - `Package Control: Add Repository` Method (Recommended)
        1. Open `Command Palette` (Default: `Primary + Shift + p`)
        2. `Package Control: Add Repository`
        3. `https://raw.githubusercontent.com/LetsZiggy/aurelia-html-syntax/main/repository-package.json`
        4. Open `Command Palette`
        5. `Package Control: Install Package`
        6. `aurelia-html-syntax`
    - "Manual" Method (Requires manual update)
        1. Download this repository through `Download ZIP`
        2. Rename folder to `aurelia-html-syntax`
        3. Move folder to `[SublimeText]/Packages` folder
            - To access `[SublimeText]/Packages` folder:
                1. Open/Restart `Sublime Text`
                2. Open the `Command Palette` (Default: `Primary + Shift + p`)
                3. `Preferences: Browse Packages`
        4. Restart `Sublime Text`
- Restart Sublime.

## How to use

The syntax is listed as `Aurelia HTML` in Sublime syntax selection list.

[ApplySyntax](https://github.com/facelessuser/ApplySyntax):
  1. `Project: Edit Project`
  2. Add syntax below:
```javascript
{
  "folders": [
    {
      "path": ".",
    },
  ],
  "settings": {
    "project_syntaxes": [
      {
        "syntax": "Aurelia HTML/AureliaHTML",
        "rules": [
          { "globmatch": "**/*.html" },
        ],
      },
    ],
  },
}
```
Manually:
  1. Open `Command Palette`
  2. `Set Syntax: Aurelia HTML`

## Development

Use packages below for syntax development.

- [PackageDev](https://github.com/SublimeText/PackageDev)
- [ScopeView](https://github.com/OdatNurd/ScopeView)
- [Syntax Highlighting Scopes Showroom](https://github.com/baleyko/syntax-highlighting-scopes-showroom)

---

This package is inspired by [Ngx HTML](https://github.com/princemaple/ngx-html-syntax) and based on [aurelia/vscode-extension](https://github.com/aurelia/vscode-extension/blob/master/syntaxes/html.json).
