# No-AI / Raw Code Configuration for VS Code

Ce dépôt contient la configuration pour désactiver complètement l'autocomplétion, les suggestions automatiques et l'assistance IA dans VS Code, afin de coder "à la main".

## Installation

1. Ouvrez VS Code.
2. Faites `Ctrl + Shift + P` (ou `Cmd + Shift + P` sur Mac).
3. Tapez et sélectionnez : **"Preferences: Open User Settings (JSON)"**.
4. Ajoutez ou remplacez les lignes suivantes dans votre fichier `settings.json` :

```json
"editor.quickSuggestions": { "other": "off", "comments": "off", "strings": "off" },
"editor.suggestOnTriggerCharacters": false,
"editor.inlineSuggest.enabled": false,
"editor.suggestSelection": "first",
"editor.suggest.showIcons": false,
"editor.suggest.showStatusBar": false,
"editor.suggest.showMethods": false,
"editor.suggest.showFunctions": false,
"editor.suggest.showConstructors": false,
"editor.suggest.showFields": false,
"editor.suggest.showVariables": false,
"editor.suggest.showClasses": false,
"editor.suggest.showStructs": false,
"editor.suggest.showInterfaces": false,
"editor.suggest.showModules": false,
"editor.suggest.showProperties": false,
"editor.suggest.showEvents": false,
"editor.suggest.showOperators": false,
"editor.suggest.showUnits": false,  
"editor.suggest.showValues": false,
"editor.suggest.showConstants": false,
"editor.suggest.showEnumMembers": false,
"editor.suggest.showEnum": false,
"editor.suggest.showKeywords": false,
"editor.suggest.showWords": false,
"editor.suggest.showColors": false,
"editor.suggest.showFiles": false,
"editor.suggest.showReferences": false,
"editor.suggest.showCustomcolors": false,
"editor.suggest.showSnippets": false,
"editor.suggest.showText": false,
"editor.suggest.showFolders": false,
"editor.suggest.showTypeParameters": false,
"editor.suggest.showUsers": false,
"editor.suggest.showIssues": false,