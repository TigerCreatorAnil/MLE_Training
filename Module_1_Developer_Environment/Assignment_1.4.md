Github PR url: https://github.com/TigerCreatorAnil/mle-training/pull/6
Github issue reference: https://github.com/TigerCreatorAnil/mle-training/issues/5

###User settings 

{
    // Enable Flake8 as linter for python
    "python.linting.flake8Enabled": true,
    "python.linting.enabled": true,
    "python.linting.flake8Args": [
        "--max-line-length=88"
    ],
    // use black for formatting python code
    "python.formatting.provider": "black",
    "python.formatting.blackArgs": [
        "--line-length=88"
    ],
    // use isort to sort imports according to the black style
    "python.sortImports.args": [
        "--profile",
        "black"
    ],
    // set tab size to 4 spaves for python code
    "editor.tabSize": 4,
    "editor.insertSpaces": true,
    //Automatically remove trailing whitespaces
    "editor.trimAutoWhitespace": true,
    // Automatically format the code when saving the file
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.organizeImports": "explicit",
        "source.fixAll": "explicit"
    },
    "files.exclude": {
        "**/__pycache__": true,
        "**/*.pyc": true
    },
    "git.autofetch": true,
    "editor.unicodeHighlight.nonBasicASCII": false,
    "editor.unicodeHighlight.invisibleCharacters": false
}

###Workspace settings


{
    "python.pythonPath": "/root/conda/envs/mle-dev/bin/python",
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.organizeImports": true
    },
    "python.formatting.provider": "black",
    "python.sortImports.args": [
        "--profile",
        "black"
    ]
}
