
#### Open User Settings
```
{
  "workbench.iconTheme": "material-icon-theme",
  "editor.formatOnSave": true,
  "files.refactoring.autoSave": false,
  "editor.wordWrap": "on",
  "workbench.editor.tabSizing": "shrink",
  "explorer.compactFolders": false,
  "editor.fontSize": 16,
  "editor.lineHeight": 26,

  // formatter

  "prettier.tabWidth": 2,
  "prettier.semi": true,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "none",
  "prettier.arrowParens": "avoid",
  "prettier.endOfLine": "auto",
  "editor.tabSize": 2,
  "editor.formatOnPaste": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "liveServer.settings.donotShowInfoMsg": true,
  "security.workspace.trust.untrustedFiles": "open",
  "editor.minimap.enabled": true,
  "liveServer.settings.CustomBrowser": "chrome",
  "[python]": {
    "editor.formatOnType": true
  },

  "files.associations": {
    "*.sql": "sql"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.suggest.showWords": false,
  "workbench.colorTheme": "SynthWave '84",
  "workbench.editorAssociations": {
    "*.exe": "default"
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash"
}
```

#### Extensões

Material Icon
Color Highlights
Image Preview
Auto Rename Tag
ES7+ React/Redux/React-Native snippets
ESLint
Next JS/TS Snippets
Prettier
Simple React Snippets
SynthWave '84
Tailwind CSS IntelliSense
Git Extension Pack

#### Bashrc

alias erc='nano ~/.bashrc'
alias rrc='source ~/.bashrc'
alias dev='npm run dev'
alias gs='git status'
alias gbr='git branch'
alias gco='git checkout'
alias gcm='git commit -m'
alias gll='git pull'
alias rgql='git restore ./src/gql'
alias clone='git clone'
alias gfront='git checkout frontend-changes'

#### Editor Config

Uma padronização para garantir uma configuração padrão para todo o código.

*Exemplo:*
![[Pasted image 20241221233016.png]]

#### Scripts Package.json

Adicionar scripts/encurtadores para serem usados no terminal seja para rodar manualmente ou utilizar em testes futuros. *(Parecido com o bashrc)*

![[Pasted image 20241221235009.png]]
