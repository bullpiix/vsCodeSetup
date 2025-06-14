# Configuracion de atajos de teclados :
```
{
  "workbench.colorTheme": "Default Light+",
  "workbench.statusBar.visible": false,
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "chat.commandCenter.enabled": false,
  "editor.minimap.enabled": false,
  "breadcrumbs.enabled": false,
  "editor.stickyScroll.enabled": false,
  "vim.easymotion": true,
  "vim.incsearch": true,
  "vim.useSystemClipboard": true,
  "vim.useCtrlKeys": true,
  "vim.hlsearch": true,
  "vim.insertModeKeyBindings": [
    {
      "before": ["}"],
      "after": ["<Esc>"]
    }
  ],"vim.normalModeKeyBindingsNonRecursive": [
    {
      "before": ["}"],
      "after": ["i"] 
    },
    {
      "before": ["r"],
      "commands": [":q!"]
    },
    {
      "before": ["s"],
      "commands": [":w"]
    },
     {
      "before": ["d"],
      "commands": ["copyFilePath"]
    },
    {
      "before": ["q"],
      "after": ["y","y"]
    },{
      "before": ["w"],
      "after": ["p"]
    },{
      "before": ["ñ"],
      "after": ["k"]
    },{
      "before": ["{"],
      "after": ["j"]
    },{
      "before": ["-"],
      "after": ["b"]
    },{
      "before": ["."],
      "after": ["e"]
    },{
      "before": ["i"],
      "after": ["<C-r>"]
     },{
      "before": ["+"],
      "after": ["o"]
      },{
      "before": ["e"],
      "after": ["d","d"]
     },{
      "before": ["a"],
      "after": ["\"","_","d","d"]
     },{
      "before": ["p"],
      "after": ["a"]
     },{
      "before": ["¿"],
      "commands": ["markdown.showPreview"]
     }
  ]
  ,"vim.visualModeKeyBindingsNonRecursive": [
    {
      "before": ["q"],
      "after": ["y"]
    },{
      "before": ["w"],
      "after": ["p"]
    },{
      "before": ["ñ"],
      "after": ["k"]
    },{
      "before": ["{"],
      "after": ["j"]
     },{
      "before": ["-"],
      "after": ["b"]
    },{
      "before": ["."],
      "after": ["e"]
    },{
      "before": ["e"],
      "after": ["d"]
      },{
      "before": ["a"],
      "after": ["\"","_","d","d"]
      },{
      "before": ["tab"],
      "after": [">","g","v"]
      },{
      "before": ["|"],
      "after": ["<","g","v"]
     },{
      "before": ["}"],
      "after": ["<Esc>"]
     }

  ]
}
```
## keybindings setup :

```
[
    {
  "key": "ctrl+1",
  "command": "workbench.action.tasks.runTask",
  "args": "Buscar archivos (fzf)"
    },
 {
  "key": "ctrl+2",
  "command": "workbench.action.tasks.runTask",
  "args": "Abrir herramienta Git"
    },   {
      "key": "ctrl+o",
      "command": "workbench.action.togglePanel"
    }
    
]
```
## taks :

guardar la setup de taks en la direccion :
```
~/.config/Code/User/tasks.json
```

setup json taks :
```
{
  "version": "2.0.0",
  "tasks": [
    {
      "label": "Buscar archivos (fzf)",
      "type": "shell",
      "command": "Documents/find_files.sh",
      "problemMatcher": [],
      "presentation": {
        "echo": true,
        "reveal": "always",
        "focus": true,
        "panel": "dedicated"
      }
    },
    {
      "label": "Abrir herramienta Git",
      "type": "shell",
      "command": "Documents/gitPyEnv/venv/bin/python",
      "args": [
        "Documents/gitPyEnv/git_tool.py"
      ],
      "problemMatcher": [],
      "presentation": {
        "echo": true,
        "reveal": "always",
        "focus": true,
        "panel": "dedicated"
      }
    }
  ]
}
```
