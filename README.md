# Adjust-VSCODE-for-Python3-Mac-


Last login: Mon Aug  8 12:27:11 on ttys003
➜  ~ sudo python3 -m pip -V
Password:
pip 22.2.1 from /Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10/site-packages/pip (python 3.10)
➜  ~ chown echo$User
usage: chown [-fhnvx] [-R [-H | -L | -P]] owner[:group] file ...
       chown [-fhnvx] [-R [-H | -L | -P]] :group file ...
➜  ~ echo $USER
adalbertoramosribeiro
➜  ~ chown adalbertoramosribeiro /Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10
chown: /Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10: Operation not permitted
➜  ~ sudo chown adalbertoramosribeiro /Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10
➜  ~ sudo python3 -m pip -V
pip 22.2.1 from /Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10/site-packages/pip (python 3.10)
➜  ~ python3 -m pip -V
pip 22.2.1 from /Library/Frameworks/Python.framework/Versions/3.10/lib/python3.10/site-packages/pip (python 3.10)
➜  ~ ls
Applications Documents    Library      Music        Pictures
Desktop      Downloads    Movies       OneDrive     Public
➜  ~ ln
usage: ln [-s [-F] | -L | -P] [-f | -i] [-hnv] source_file [target_file]
       ln [-s [-F] | -L | -P] [-f | -i] [-hnv] source_file ... target_dir
       link source_file target_file
➜  ~ which python3
/Library/Frameworks/Python.framework/Versions/3.10/bin/python3
➜  ~



{
    "workbench.iconTheme": "vscode-icons",
    "[html]": {
        "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "workbench.colorTheme": "Dracula Soft",
    "editor.wordWrap": "on",
    "files.autoSave": "afterDelay",
    "diffEditor.wordWrap": "on",
    "editor.tabSize": 2,
    "[css]": {
        "editor.defaultFormatter": "stylelint.vscode-stylelint"
    },
    "code-runner.clearPreviousOutput": true,
    "editor.minimap.enabled": false,
    "git.confirmSync": false,
    "prettier.singleQuote": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "explorer.confirmDelete": false,
    "[javascriptreact]": {
        "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "tabnine.experimentalAutoImports": true,
    "editor.formatOnSave": true,
    "html.format.unformatted": "",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "[javascript]": {
        "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "eslint.format.enable": true,
    "editor.formatOnPaste": true,
    "git.autofetch": true,
    "git.enableSmartCommit": true,
    "json.schemas": [],
    "[python]": {
        "editor.wordBasedSuggestions": false
    },
    "python.defaultInterpreterPath": "/Library/Frameworks/Python.framework/Versions/3.10/bin/python3",
    "window.zoomLevel": 2,
    "python.pythonPath": "python3",
    "code-runner.executorMap": {
        "python3": "/Library/Frameworks/Python.framework/Versions/3.10/bin/python3",
    "python": "/Library/Frameworks/Python.framework/Versions/3.10/bin/python3"    
    }
}
