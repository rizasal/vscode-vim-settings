# vscode-vim-settings
Personal settings.json for vscode

{

    "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
    "window.zoomLevel": 1,
    "editor.tabSize": 2,
    "files.insertFinalNewline": true,
    "files.eol": "\n",
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": false,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": false,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": false,
    "typescript.format.insertSpaceBeforeFunctionParenthesis": false,
    "typescript.preferences.quoteStyle": "single",
    "typescript.format.insertSpaceAfterFunctionKeywordForAnonymousFunctions": false,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBraces": false,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    "http.proxySupport": "off",
    "vim.normalModeKeyBindingsNonRecursive": [
        {
            "before": ["<leader>", "o"],
            "after": [],
            "commands": [
                {
                    "command": "workbench.action.quickOpen"
                }
            ]
        },{
            "before": ["Z", "Z"],
            "commands": [
                ":wq"
            ]
        },{

            "before": ["leader", "w"],
            "commands": [
                "workbench.action.files.save",
            ]
        }],
        "vim.leader": "<space>",
        "vim.handleKeys": {
        "<C-a>": false,
        "<C-f>": false
        },
        "vim.insertModeKeyBindings": [
            {
                "before": ["j", "j"],
                "after": ["<Esc>"]
            }
        ]
}

