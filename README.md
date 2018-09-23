# Alloy 

This extension supports the [Alloy](http://alloytools.org/) modelling language.

## Features
- Running Alloy commands from VS Code
- Viewing results (instances/counterexamples)
- Editor integrated error reporting

![executing alloy commands](https://imgur.com/download/dtPZEBW)

- Go to Definition support

![go to definition support](https://imgur.com/download/Dyq9b0w)



- Find References support
- Rename support (works across files)
<!-- ![rename support](https://imgur.com/download/vw3Mpf7) -->
<!-- ![find references support](https://imgur.com/download/LhpXCZX) -->

![ref, rename support](https://imgur.com/download/T2ZHszv)

- Document outline/symbol search support
- Folder symbol search support 

<!-- ![symbol support](https://imgur.com/download/1booynh) -->
![symbol support](https://imgur.com/download/Kze9f6e)

(Syntax highlighting provided by [alloy-vscode](https://marketplace.visualstudio.com/items?itemName=DongyuZhao.alloy-vscode))

This extension is bundled with a [custom version](https://github.com/s-arash/org.alloytools.alloy/tree/ls) of the Alloy analyzer JAR that supports the Language Server Protocol.
## Tips

- To change Alloy settings (SAT solver, allow warnings, etc.) open the command palette (<kbd>Ctrl</kbd>/<kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>), and find the command `Open Alloy Editor`. This will open the bundled Alloy analyzer.

- To select an Alloy command from a drop down menu, use the command `List Alloy Commands`.

- To execute all Alloy commands in an Alloy file, use the command `Execute All Alloy Commands`.

- Code lens can be disabled by changing the preference `alloy.commandHighlightMode` to `link` (a good option if you don't like the code moving vertically while you type).

## Requirements

Java (8 or higher) must be installed and included in PATH.

