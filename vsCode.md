# Visual Studio Code
Download the latest version on the [official website](https://code.visualstudio.com/download). Unzip the downloaded file and move the Visual Studio Code.app to Application folder.

## My Preferences Settings
```json
//
// Editor
//
"editor.rulers": [80,100,120],
// The number of spaces a tab is equal to. This setting is overridden
// based on the file contents when `editor.detectIndentation` is true.
"editor.tabSize": 2,
// Insert spaces when pressing Tab. This setting is overriden
// based on the file contents when `editor.detectIndentation` is true.
"editor.insertSpaces": true,
// When opening a file, `editor.tabSize` and `editor.insertSpaces`
// will be detected based on the file contents. Set to false to keep
// the values you've explicitly set, above.
"editor.detectIndentation": false,
"files.insertFinalNewline": true,
"workbench.colorCustomizations": {
    "editorRuler.foreground": "#ff7ca8"
},
//
// Terminal
//
"terminal.external.osxExec": "iTerm.app",
"terminal.integrated.defaultProfile.osx": "zsh",
"terminal.explorerKind": "external",
"terminal.integrated.fontFamily": "Meslo LG M for Powerline",
```

[Go Back](./README.md)
