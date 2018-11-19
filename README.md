# LS-DYNA syntax highlighting for VSCode
This is an LS-DYNA input file `.k` syntax highlighting for [Visual Studio Code](https://code.visualstudio.com).
The package is generated using [Yo Code](https://code.visualstudio.com/docs/extensions/yocode). 
The `.tmlanguage` file used in this package is coppied from [here](https://github.com/bendeaton/LS-DYNA-Sublime). 

# Settings
You can add the following lines to `User Settings` to hide indent guide and add 10-character wide rulers.
```json
    "[ls-dyna]": {
        "editor.renderIndentGuides": false,
        "editor.rulers": [
            10, 20, 30, 40, 50, 60, 70, 80
            ]
    }
```

# Installation

Copy the repository folder to the extension directory:
* on Windows `%USERPROFILE%\.vscode\extensions`
* on Mac/Linux `$HOME/.vscode/extensions`
