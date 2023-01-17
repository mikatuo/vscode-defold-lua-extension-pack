# Defold Lua Extension Pack

This extension pack packages some of the most popular [Defold](http://defold.com/) extensions.

## Recommended Settings

Feel free to copy and paste them into your `.vscode/settings.json` file.

```json
{
    "editor.snippetSuggestions": "bottom",
    "Lua.diagnostics.ignoredFiles": "Disable",
    "Lua.diagnostics.libraryFiles": "Disable",
    "Lua.completion.callSnippet": "Replace",
    "Lua.diagnostics.globals": [
        "init",
        "final",
        "update",
        "fixed_update",
        "on_message",
        "on_input",
        "on_reload"
    ],
    "search.exclude": {
        "**/build/**": true,
        "patches/": true,
        "**/*.collection": true,
        "**/*.atlas": true,
        "**/icon_*.png": true
    }
}
```  

## What's Included

- [sumneko.lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) - A powerful Lua language server with IntelliSense.
- [thejustinwalsh.textproto-grammer](https://marketplace.visualstudio.com/items?itemName=thejustinwalsh.textproto-grammer) - Textual Protobuf syntax highlighting.
- [slevesque.shader](https://marketplace.visualstudio.com/items?itemName=slevesque.shader) - Shader languages support.
- [dtoplak.vscode-glsllint](https://marketplace.visualstudio.com/items?itemName=dtoplak.vscode-glsllint) - Linting of OpenGL Shading Language.
- [koihik.vscode-lua-format](https://marketplace.visualstudio.com/items?itemName=Koihik.vscode-lua-format) - Lua code formatter.

**Credit**

This extension pack is based on the guide [How to turn Visual Studio Code into Defold IDE](https://github.com/astrochili/defold-vscode-guide) by [astrochili](https://github.com/astrochili).

<hr>

The Defold name and logo are registered trademarks of the Defold Foundation.