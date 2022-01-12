# Extensions for Angular developers @ Trivadis

Useful VS Code extensions for any Angular developer.

<img src="https://github.com/Trivadis/vscode-ngtvd-extensions/blob/master/images/TrivadisAngular_logo-01.jpg?raw=true" style="height: 150px" />

[Your way to an Angular Hero](https://www.trivadis-training.com/en/training/advanced-angular-schulung-ad-angular-adv)

## File settings

You can use the following settings in your VS Code (File -> Preferences -> Settings)

```json
    "files.exclude": {
        "**/.git": true,
        "**/.DS_Store": true,
        "**/*.js": {
            "when": "$(basename).ts"
        },
        "**/*.js.map": {
            "when": "$(basename)"
        }
    },
    "files.trimTrailingWhitespace": true,
    "prettier.singleQuote": true,
    "prettier.printWidth": 100,
    "editor.formatOnSave": true,
```

## Included Extensions

[Angular v12 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

[Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

## Authors

Thomas Gassmann
[Trivadis](https://trivadis.com)
