# Extensions for Angular developers @ Trivadis

Useful VS Code extensions for any Angular developer.

<img src="https://github.com/TrivadisCloud/vscode-ngtvd-extensions/blob/master/images/TrivadisAngular_logo-01.jpg?raw=true" style="height: 150px" />

[Your way to an Angular Hero](https://m.trivadis.com/angular-schulung)

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
    "files.defaultLanguage": "typescript",
	"files.hotExit": "off",
    "workbench.iconTheme": "vscode-icon-theme",
    "files.trimTrailingWhitespace": true,
    "prettier.singleQuote": true,
    "prettier.printWidth": 100,
    "editor.formatOnSave": true,
```

## Included Extensions

[Angular v5 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

[Angular Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)

[tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)

[Chrome Debugger](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

[Studio Icons](https://marketplace.visualstudio.com/items?itemName=jtlowe.vscode-icon-theme)

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

## Authors

Thomas Gassmann
[Angular@Trivadis](https://m.trivadis.com/angular)
