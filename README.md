# My VScode Settings

This repository contains My VScode settings, including adjustiment font, theme and extensions.

## Pre Requirements

- VScode installed [Download Click here](https://code.visualstudio.com/)

## VScode Settigns

Copy and paste the settings bellow to the your file 'settings.json' of VScode:

'''
{
  "workbench.colorTheme": "OM Theme (Default Dracula Italic)",
  "workbench.iconTheme": "symbols",
  "tabnine.experimentalAutoImports": true,
  "editor.guides.bracketPairs": true,
  "miramac.node.clearOutput": true,
  "editor.fontFamily": "Cascadia Code",
  "editor.tabSize": 2,
  "editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss04', 'ss05', 'ss06', 'zero', 'onum'",
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.fixAll.eslint": "explicit"
  },
  "editor.tokenColorCustomizations": {
    "comments": {"fontStyle": "italic", "foreground": "#757575"},
    "textMateRules": [{
      "scope": ["constant", "emphasis"],
      "settings": {"fontStyle": "italic"},
    }, {
      "scope": ["support.variable"],
      "settings": {"foreground": "#F8F8F2"},
    }, {
      "scope": ["variable.other.constant"],
      "settings": {"fontStyle": "italic", "foreground": "#8BE9FD"},
      
    }, {
      "scope": ["entity.name.type.class", "entity.name.class", "entity.name.type", "entity.name.function", "support.type.object.module.js"],
      "settings": {"fontStyle": "italic", "foreground": "#50FA7B"},
    }, {
      "scope": ["storage"],
      "settings": {"fontStyle": "italic"},
    }, {
      "scope": ["support.variable.property"],
      "settings": {"foreground": "#BD93F9",}
    }],
  },
  "workbench.editor.enablePreview": false,
  "explorer.compactFolders": false,
  "editor.minimap.enabled": false,
  "symbols.hidesExplorerArrows": false,
  "editor.lineHeight": 1.5,
  "breadcrumbs.enabled": false,
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "workbench.activityBar.location": "hidden",
  "apc.stylesheet": {
    ".title-label > h2": "display: none",
  },
  "apc.listRow": {
    "height": 24
  },
  "workbench.colorCustomizations": {
    "activityBar.background": "#121212",
    "activityBar.foreground": "#f2f2f2",
    "activityBar.inactiveForeground": "#A6A6A6",
    "activityBarBadge.foreground": "#121212",
    "activityBarBadge.background": "#A6A6A6",
    "activityBar.border": "#1f1f1f",
    "activityBar.activeBackground": "#404040",
    "activityBar.activeBorder": "#f2f2f2",
    "sideBar.background": "#1f1f1f",
    "sideBar.foreground": "#f2f2f2",
    "sideBarSectionHeader.background": "#1f1f1f",
    "sideBarSectionHeader.foreground": "#1f1f1f",
    "focusBorder": "#f2f2f2",
    "sideBarTitle.foreground": "#f2f2f2",
    "sideBar.border": "#1f1f1f",
    "list.inactiveSelectionBackground": "#404040",
    "list.inactiveSelectionForeground": "#f2f2f2",
    "list.hoverBackground": "#404040",
    "list.hoverForeground": "#f2f2f2",
    "list.activeSelectionBackground": "#404040",
    "list.activeSelectionForeground": "#f2f2f2",
    "list.focusAndSelectionOutline": "#404040",
    "tree.indentGuidesStroke": "#A6A6A6",
    "statusBar.foreground": "#f2f2f2",
    "statusBar.background": "#121212",
    "titleBar.activeBackground": "#121212",
    "titleBar.activeForeground": "#f2f2f2",
    "titleBar.border": "#121212",
    "titleBar.inactiveBackground": "#121212",
    "titleBar.inactiveForeground": "#A6A6A6",
    "menu.foreground": "#f2f2f2",
    "menu.background": "#101010",
    "menu.selectionForeground": "#f2f2f2",
    "menu.selectionBackground": "#121212",
    "menu.selectionBorder": "#f2f2f2",
    "menu.separatorBackground": "#404040",
    "menu.border": "#404040",
    "editorGroupHeader.tabsBackground": "#121212",
    "editorGroupHeader.tabsBorder": "#121212",
    "editor.background": "#121212",
    "tab.activeForeground": "#f2f2f2",
    "tab.border": "#121212",
    "tab.activeBackground": "#121212",
    "tab.activeBorder": "#121212",
    "tab.activeBorderTop": "#121212",
    "tab.inactiveBackground": "#1f1f1f",
    "tab.inactiveForeground": "#A6A6A6",
    "tab.hoverBackground": "#121212",
    "tab.hoverForeground": "#f2f2f2",
    "tab.hoverBorder": "#121212",
    "breadcrumb.background": "#121212",
    "breadcrumb.foreground": "#f2f2f2",
    "breadcrumb.focusForeground": "#f2f2f2",
    "editorGroupHeader.border": "#121212",
    "editorLineNumber.foreground": "#A6A6A6",
    "editorLineNumber.activeForeground": "#f2f2f2",
    "editor.selectionBackground": "#404040",
    "editor.inactiveSelectionBackground": "#404040",
    "editor.lineHighlightBackground": "#1f1f1f",
    "editor.lineHighlightBorder": "#1f1f1f",
    "editorIndentGuide.background1": "#404040",
    "editorIndentGuide.activeBackground1": "#A6A6A6",
    "editor.hoverHighlightBackground": "#404040",
    "editorSuggestWidget.background": "#101010",
    "editorSuggestWidget.border": "#404040",
    "editorSuggestWidget.foreground": "#A6A6A6",
    "editorSuggestWidget.highlightForeground": "#f2f2f2",
    "editorSuggestWidget.selectedBackground": "#404040",
    "editorSuggestWidget.focusHighlightForeground": "#f2f2f2",
    "editorSuggestWidget.selectedForeground": "#a6a6a6",
    "editorSuggestWidget.selectedIconForeground": "#f2f2f2",
    "editorWidget.background": "#101010",
    "input.background": "#404040",
    "input.border": "#101010",
    "input.foreground": "#f2f2f2",
    "input.placeholderForeground": "#f2f2f2",
    "inputOption.activeBackground": "#121212",
    "inputOption.activeBorder": "#A6A6A6",        
    "panel.background": "#121212",
    "panel.border": "#404040",
    "panelTitle.inactiveForeground": "#A6A6A6",
    "panelTitle.activeBorder": "#f2f2f2",
    "badge.background": "#A6A6A6",
    "badge.foreground": "#121212",
    "notifications.background": "#101010",
    "notifications.foreground": "#f2f2f2",
    "notificationToast.border": "#A6A6A6",
    "editorHoverWidget.background": "#101010",
    "editorHoverWidget.border": "#A6A6A6",
    "terminal.background": "#121212",
    "dropdown.background": "#121212",
    "dropdown.border": "#f2f2f2",
    "dropdown.listBackground": "#121212",
    "gitDecoration.ignoredResourceForeground": "#818181",
    "statusBar.noFolderBackground": "#121212"
  },
  "window.menuBarVisibility": "compact",
  "editor.cursorStyle": "block",
}
'''

OBS 1: The options 'workbench.colorCustomizations' and 'editor.tokenColorCustomizations' is optional.
OBS 2: The option 'apc' only it works with the extension 'Apc Customize UI++'.

##  Extensions

- Tabnine: AI Autocomplete & Chat for Javascript, Python
- Apc Customize UI++
- Auto Close Tag
- Auto Rename Tag
- Code Runner
- Color Highlight
- EditorConfig for VS Code
- ESLint
- Live Server
- Material Icon Theme
- Node.js Exec
- npm Intellisense
- Om Theme (A Darker Dracula Theme)
- Pylance
- Python
- Python Debugger
- Reload
- REST Client
- Symbols
- Tailwind CSS IntelliSense
- vscode-styled-components

## Font Family

- Cascadia Code [Download Click Here](https://github.com/microsoft/cascadia-code)
