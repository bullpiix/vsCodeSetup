# vsCodeSetup
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
      "before": ["0"],
      "after": ["<Esc>"]
    }
  ],"vim.normalModeKeyBindingsNonRecursive": [
    {
      "before": ["0"],
      "after": ["i"] 
    },{
      "before": ["2"],
      "after": ["$"]
    },{
      "before": ["1"],
      "after": ["^"]
    },{
      "before": ["x"],
      "after": ["v"]
    },{
      "before": ["Space","{"],
      "after": ["<C-w>","l"]
    },{
      "before": ["<Space>","ñ"],
      "after": ["<C-w>","h"]
    },{
      "before": ["c"],
      "commands": [":vsplit<CR>"]
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
     },{
        "before": ["Space","e"],
      "after": ["i","<",">","Left"]
     },{
        "before": ["Space","w"],
      "after": ["V"]
     },{
        "before": ["Space","q"],
      "after": ["v"]
     },{
        "before": ["|"],
      "commands": ["editor.action.startFindReplaceAction"]
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
     },{
      "before": ["2"],
      "after": ["$"]
    },{
      "before": ["1"],
      "after": ["^"]
    }

  ],
  "security.workspace.trust.untrustedFiles": "open",
  "warmUp.changeCount": "15",
  "warmUp.switchProgrammingLanguage": "python",
  "warmUp.changeTypingMode": "code snippets"
}

