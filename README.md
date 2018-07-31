# expr-vscode

expr assembly language support for Visual Studio Code

## Features

![Syntax example](https://raw.githubusercontent.com/heztet/expr-vscode/master/example.png)

This package includes the grammar for the Motorola expr core instruction set, defined in the [expr/exprRM manual](http://www.nxp.com/docs/en/reference-manual/exprRM.pdf).

Modified from Zachary Polikarpus' [Atom library](https://github.com/zpolygon95/language-expr).

## Creating a language extension

There's plenty of helpful examples in the Visual Code documentation. Start with their [extension example](https://code.visualstudio.com/docs/extensions/example-hello-world) and look at other tmLanguage.json files to get an idea of how to write them. The names in the grammar can be found in the [TextMate manual](https://manual.macromates.com/en/language_grammars). To debug your extension, press `F5` and load an example file. Use the `Developer: Inspect TM scopes` tool in the Command Pallete to debug your settings.
