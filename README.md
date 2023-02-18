# Web Design Essentials - Extension Pack for Visual Studio Code

[![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/Gydunhn.html-essentials?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.html-essentials) [![Installs](https://flat.badgen.net/vs-marketplace/i/Gydunhn.html-essentials?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.html-essentials) [![Downloads](https://flat.badgen.net/vs-marketplace/d/Gydunhn.html-essentials?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.html-essentials) [![Rating](https://flat.badgen.net/vs-marketplace/rating/Gydunhn.html-essentials?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.html-essentials)

This extension pack for Visual Studio Code adds extensions that are useful for Web Design projects. I reserve the right to update the extensions pack contents up to my own discretion. This extension is for my personal use, I think it's great if it works for other people too.

## Reasons

The [HTML Essentials extension pack] was made to automate and standardize the installation phase of the essential HTML & CSS extensions for Visual Studio Code every time a new member joins the team, or one of them restores a laptop, or exchanges it for a new one.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

## **settings.json**

It is strongly recommended that these settings be used in your workspace. You must copy and paste them, and if you need to adjust something you will already know where to do it.

``` json
{
    /**
     * HTML Essentials Config
     */
    "[css]": {
        "editor.defaultFormatter": "vscode.css-language-features"
    },
    "[less]": {
        "editor.defaultFormatter": "vscode.css-language-features"
    },
    "[scss]": {
        "editor.defaultFormatter": "vscode.css-language-features"
    },
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "css.hover.documentation": true,
    "css.lint.important": "warning",
    "css.lint.importStatement": "warning",
    "less.hover.documentation": true,
    "less.lint.important": "warning",
    "less.lint.importStatement": "warning",
    "scss.hover.documentation": true,
    "scss.lint.important": "warning",
    "scss.lint.importStatement": "warning",
    "html.hover.documentation": true,
    "htmlhint.documentSelector": [
        "html",
        "htm"
    ],
    "htmlhint.options": {
        "src-not-empty": true
    }
}
```

If you are using the [VSC-Essentials] extension pack additionally, you can see the complete settings file [here] ([settings.json])

## Note

The [VSC-Essentials] project was used as a template for this one.

## Included

This extension pack includes the following extensions:

| Extension              | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HTMLHint               | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/HTMLHint.vscode-htmlhint?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=HTMLHint.vscode-htmlhint) [![Installs](https://flat.badgen.net/vs-marketplace/i/HTMLHint.vscode-htmlhint?color=blue)](https://marketplace.visualstudio.com/items?itemName=HTMLHint.vscode-htmlhint) [![Rating](https://flat.badgen.net/vs-marketplace/rating/HTMLHint.vscode-htmlhint?color=blue)](https://marketplace.visualstudio.com/items?itemName=HTMLHint.vscode-htmlhint)                                           |
| HTML CSS Support       | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/ecmel.vscode-html-css?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) [![Installs](https://flat.badgen.net/vs-marketplace/i/ecmel.vscode-html-css?color=blue)](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) [![Rating](https://flat.badgen.net/vs-marketplace/rating/ecmel.vscode-html-css?color=blue)](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)                                                             |
| Auto Complete Tag      | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/formulahendry.auto-complete-tag?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag) [![Installs](https://flat.badgen.net/vs-marketplace/i/formulahendry.auto-complete-tag?color=blue)](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag) [![Rating](https://flat.badgen.net/vs-marketplace/rating/formulahendry.auto-complete-tag?color=blue)](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag) |
| Highlight Matching Tag | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/vincaslt.highlight-matching-tag?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag) [![Installs](https://flat.badgen.net/vs-marketplace/i/vincaslt.highlight-matching-tag?color=blue)](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag) [![Rating](https://flat.badgen.net/vs-marketplace/rating/vincaslt.highlight-matching-tag?color=blue)](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag) |
| Color Highlight        | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/naumovs.color-highlight?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Installs](https://flat.badgen.net/vs-marketplace/i/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Rating](https://flat.badgen.net/vs-marketplace/rating/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)                                                 |
| CSS Peek               | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/pranaygp.vscode-css-peek?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) [![Installs](https://flat.badgen.net/vs-marketplace/i/pranaygp.vscode-css-peek?color=blue)](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) [![Rating](https://flat.badgen.net/vs-marketplace/rating/pranaygp.vscode-css-peek?color=blue)](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)                                           |
| css-snippets           | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/joy-yu.css-snippets?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=joy-yu.css-snippets) [![Installs](https://flat.badgen.net/vs-marketplace/i/joy-yu.css-snippets?color=blue)](https://marketplace.visualstudio.com/items?itemName=joy-yu.css-snippets) [![Rating](https://flat.badgen.net/vs-marketplace/rating/joy-yu.css-snippets?color=blue)](https://marketplace.visualstudio.com/items?itemName=joy-yu.css-snippets)                                                                         |

[VSC-Essentials]: https://github.com/Gydunhn/VSC-Essentials
[HTML Essentials extension pack]: https://marketplace.visualstudio.com/items?itemName=Gydunhn.html-essentials
[here]: /.vscode/settings.json
[settings.json]: /.vscode/settings.json
