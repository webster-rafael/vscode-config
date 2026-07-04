# vscode-config

{
  "workbench.iconTheme": "material-icon-theme",
  "settingsSync.ignoredExtensions": [],
  "json.schemas": [],
  "symbols.hidesExplorerArrows": false,
  "files.autoSave": "afterDelay",
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "deno.enable": true,
  "deno.lint": true,
  "deno.path": "C:\\Users\\webst\\.deno\\bin\\deno.exe",
  "editor.lineHeight": 1.9,
  "editor.rulers": [80, 120],
  "workbench.startupEditor": "newUntitledFile",
  "editor.renderLineHighlight": "gutter",
  "editor.fontLigatures": true,
  "workbench.editor.labelFormat": "short",
  "editor.semanticHighlighting.enabled": false,
  "breadcrumbs.enabled": false,
  "editor.minimap.enabled": false,
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "visible",
  "workbench.statusBar.visible": true,
  "[prisma]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "Prisma.prisma",
  },
  "tailwindCSS.experimental.classRegex2": [
    [
      "tv\\(([^)]*)\\)",
      "([\"'`][^\"'`]*.*?[\"'`])",
      "[\"'`]([^\"'`]*).*?[\"'`]",
    ],
    "class:\\s*?[\"'`]([^\"'`]*).*?,",
  ],

  "tailwindCSS.experimental.classRegex": [
    ["className\\s*:\\s*['\"]([^'\"]*)['\"]"],
  ],

  "apc.electron": {
    "titleBarStyle": "hiddenInset",
  },

  "apc.font.family": "Inter",
  "apc.stylesheet": {
    ".title-label > h2": "display: none",
    ".editor-actions": "display: none",
    ".pane-body": "padding: 5px",
    ".pane-header": "padding: 0 8px",
    ".split-view-view:first-child .pane-header": "display: none !important;",
    ".monaco-list-row": "border-radius: 8px;",
  },
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "JetBrainsMono NF",
  "terminal.integrated.env.windows": {},
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "editor.formatOnSave": true,
  "console-ninja.featureSet": "Community",
  "editor.stickyScroll.enabled": false,
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 100,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "workbench.editor.editorActionsLocation": "hidden",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[dockercompose]": {
    "editor.defaultFormatter": "ms-azuretools.vscode-docker",
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "terminal.integrated.profiles.windows": {
    "PowerShell": {
      "source": "PowerShell",
      "icon": "terminal-powershell",
    },
    "Command Prompt": {
      "path": [
        "${env:windir}\\Sysnative\\cmd.exe",
        "${env:windir}\\System32\\cmd.exe",
      ],
      "args": [],
      "icon": "terminal-cmd",
    },
    "Git Bash": {
      "source": "Git Bash",
    },
    "Windows PowerShell": {
      "path": "C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
    },
    "Ubuntu (WSL)": {
      "path": "C:\\WINDOWS\\System32\\wsl.exe",
      "args": ["-d", "Ubuntu"],
    },
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "icon": "terminal-bash",
    },
    "zsh": {
      "path": "zsh",
      "icon": "terminal-bash",
    },
    "fish": {
      "path": "fish",
    },
  },
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "github.copilot.chat.completionContext.typescript.mode": "on",
  "editor.inlineSuggest.suppressSuggestions": true,
  "terminal.integrated.defaultProfile.linux": "bash",

  "git.verboseCommit": true,
  "github.copilot.chat.commitMessageGeneration.instructions": [
    {
      "text": "Use conventional commit message format and in English language.",
    },
  ],
  "debug.javascript.terminalOptions": {},
  "terminal.external.linuxExec": "zsh",
  "terminal.integrated.suggest.enabled": true,
  "workbench.navigationControl.enabled": false,
  "settingsSync.ignoredSettings": [],
  "workbench.settings.applyToAllProfiles": [],
  "terminal.integrated.env.linux": {},
  "liveServer.settings.AdvanceCustomBrowserCmdLine": "",
  "git.confirmSync": false,
  "editor.unicodeHighlight.allowedCharacters": {
    " ": true,
  },
  "git.autofetch": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "typescript.preferences.importModuleSpecifier": "non-relative",
  "cody.suggestions.mode": "auto-edit",
  "github.copilot.nextEditSuggestions.enabled": true,
  "amp.url": "https://ampcode.com/",
  "amp.tab.enabled": true,
  "terminal.integrated.suggest.cdPath": "off",
  "explorer.compactFolders": false,
  "gitlens.ai.model": "vscode",
  "gitlens.ai.vscode.model": "copilot:gpt-4.1",
  "git.suggestSmartCommit": false,
  "window.menuBarVisibility": "compact",
  "window.commandCenter": false,
  "claudeCode.preferredLocation": "sidebar",
  "chat.viewSessions.orientation": "stacked",
  "json.schemaDownload.trustedDomains": {
    "https://schemastore.azurewebsites.net/": true,
    "https://raw.githubusercontent.com/": true,
    "https://www.schemastore.org/": true,
    "https://json.schemastore.org/": true,
    "https://json-schema.org/": true,
    "https://biomejs.dev": true,
  },
  "go.toolsManagement.autoUpdate": true,
  "launch": {
    
    "configurations": [],
    "compounds": []
  },
}
