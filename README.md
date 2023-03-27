# Ionide + vscode-solution-explorer
[![Version](https://vsmarketplacebadges.dev/version-short/spencer-farley.ionide-and-vscode-solution-explorer.svg)](https://marketplace.visualstudio.com/items?itemName=spencer-farley.ionide-and-vscode-solution-explorer)

[Ionide](https://marketplace.visualstudio.com/items?itemName=Ionide.Ionide-fsharp) is a wonderful editor for F# and [vscode-solution-explorer](https://marketplace.visualstudio.com/items?itemName=fernandoescolar.vscode-solution-explorer) is a featureful tree view for .NET solutions and projects. 
This extension installs both with a bit of configuration to turn off the default Ionide tree view.

Yes, I know that Ionide includes a tree view for solutions and projects, but vscode-solution-explorer supports more features like
- Listing all kinds of files (i.e. markdown, text, gitignore, notebooks, etc)
- Creating many kinds of files with templates
- Package management
- Project reference management
- Differentiating linked files
- A broader range of hot keys (i.e. `f2` to rename, `delete` to delete a file)

## Turning the Ionide Tree View On Or Off

If you decide that you want both the Ionide tree view and the vscode-solution-explorer view then you can 
easily turn the ionide view back on. The configuration setting ID is `FSharp.enableTreeView`.

Likewise, if the Ionide explorer is still showing for some reason (perhaps the setting was set somewhere else)
just set `FSharp.enableTreeView` to false/unchecked.
