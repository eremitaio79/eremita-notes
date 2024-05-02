# Notas sobre Visual Studio Code

## Exemplo de personalização do arquivo settings.json
```
{
    "editor.fontSize": 14,
    "editor.fontWeight": "550",
    "editor.lineHeight": 1.5,
    "editor.minimap.renderCharacters": false,
    "editor.minimap.showSlider": "always",
    "editor.fontFamily": "'JetBrains Mono Medium', Consolas, 'Courier New', monospace",
    "editor.rulers": [80, 100],
    // "editor.rulers": [80, 100, 120],
    "workbench.colorCustomizations": {
        "editorLineNumber.activeForeground": "#ef463a",
        "editor.lineHighlightBackground": "#b4e7ff",
        "editor.selectionHighlightBackground": "#ffe6ad",
        "editor.selectionBackground": "#ffc012",
        "editor.inactiveSelectionBackground": "#68ff93",
        "editor.line": "#afddfb",
        "editorRuler.foreground": "#d6d6d6",
        "editor.background": "#ececec",
        // "sideBar.background": "#dadada",
        // "sideBar.background": "#e8e8e8",
        "sideBar.background": "#ececec",
        "minimap.background": "#e8e8e8",
        "tab.activeForeground": "#505050",
        "tab.activeBackground": "#addeff",
        "tab.activeBorder": "#00538a",
        "tab.inactiveBackground": "#ebebeb",
        "tab.inactiveForeground": "#505050",
        "tab.lastPinnedBorder": "#007acc",
        // "activityBar.background": "#d0d0d0",
        // "activityBar.background": "#e8e8e8",
        "activityBar.background": "#e8e8e8",
        "activityBar.foreground": "#505050",
        // "activityBar.activeBackground": "#dadada",
        "activityBar.activeBackground": "#ececec",
        // "activityBar.activeBackground": "#ececec",
        "statusBar.background": "#505050",
        // "activityBar.activeFocusBorder": "#007acc"
        //"activityBar.border": "#007acc"
    },
    "intelephense.phpdoc.classTemplate": {
        "summary": "$1",
        "tags": [
            "@package ${1:$SYMBOL_NAMESPACE}"
        ]
    },
    "debug.javascript.terminalOptions": {
    },
    "workbench.iconTheme": "vscode-icons",
    "workbench.colorTheme": "Visual Studio Light",
    "editor.wordWrap": "off",
    "editor.wordWrapColumn": 200,
    "php.suggest.basic": false,
    "editor.linkedEditing": true,
    "explorer.confirmDelete": false,
    "terminal.integrated.cursorStyle": "underline",
    "terminal.integrated.fontSize": 17,
    "terminal.integrated.fontWeight": "bold",
    "google-translate.firstLanguage": "en",
    "google-translate.secondLanguage": "en",
    "gitlens.graph.minimap.additionalTypes": [
        "localBranches",
        "stashes",
        "remoteBranches",
        "tags"
    ],
    "editor.stickyScroll.enabled": false,
}
```