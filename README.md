This extension provides rich support for the [Alloy](http://alloytools.org/) specification language.

**Note:** This extension supports **Alloy 6**. If your specifications are not compatible with Alloy 6, use the [Alloy5 extension](https://marketplace.visualstudio.com/items?itemName=ArashSahebolamri.alloy5) instead.
## Features
- Running Alloy commands from VS Code (using mouse or key combo <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>A</kbd> <kbd>E</kbd>)
- Viewing results (instances/counterexamples)
- Editor integrated error reporting

![executing alloy commands](https://github.com/s-arash/VSCodeAlloyExtension/raw/master/media_readme/executing-commands.gif)

- Go to Definition 
- Support for Alloy Markdown files

![go to definition and markdown support](https://github.com/s-arash/VSCodeAlloyExtension/raw/master/media_readme/alloy-markdown2.gif)

- Find References 
- Rename (works across files)
<!-- ![rename](https://imgur.com/download/vw3Mpf7) -->
<!-- ![find references](https://imgur.com/download/LhpXCZX) -->

![ref, rename](https://github.com/s-arash/VSCodeAlloyExtension/raw/master/media_readme/demo-ref-rename2.gif)

- Document outline/symbol search
- Folder symbol search  

<!-- ![symbol](https://imgur.com/download/1booynh) -->
![symbol](https://github.com/s-arash/VSCodeAlloyExtension/raw/master/media_readme/demo-symbol3.gif)

(Syntax highlighting provided by [alloy-vscode](https://marketplace.visualstudio.com/items?itemName=DongyuZhao.alloy-vscode))

This extension is bundled with a [custom version](https://github.com/s-arash/org.alloytools.alloy/tree/ls) of the Alloy analyzer JAR that implements the Language Server Protocol.
## Tips

- To change Alloy settings (SAT solver, allow warnings, etc.) open the command palette (<kbd>Ctrl</kbd>/<kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>), and find the command `Open Alloy Editor`. This will open the bundled Alloy analyzer.

- To execute the Alloy command under cursor, use the command `Execute Current Alloy Command` (key combo <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>A</kbd> <kbd>E</kbd>).

- To select an Alloy command from a drop down menu, use the command `List Alloy Commands`.

- To execute all Alloy commands in an Alloy file, use the command `Execute All Alloy Commands`.

- Code lens can be disabled by changing the preference `alloy.commandHighlightMode` to `link` (a good option if you don't like the code moving vertically while you type).

## Requirements

Java (8 or higher) must be installed and included in PATH.

