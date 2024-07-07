# Koan
This a vscode extension to provide syntax highlighting for the koan programming language within vsc. Eventually this extension will also include lsp support

# Installation
To install this extension, run these commands:


```bash
git clone https://github.com/TogarashiPepper/koan-vscode.git
cd koan-vscode
npx @vscode/vsce -- package
code --install-extension *.vsix
rm -i *.vsix
```

And tada! You're done! LSP Support coming soon™.
