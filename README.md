# LaTeX Templates

Within are templates for creating different kinds of documents with LaTeX, as well as instructions for installing any necessary dependencies. Templates are arranged in folders.

## Setup

It is recommended to install LaTeX without the GUI tools and use an editor such as VS Code with the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension. If you do so, including the following in your workspace settings will be helpful:

```json
"settings": {
  "files.exclude": {
    "**/*.aux": true,
    "**/*.bbl": true,
    "**/*.blg": true,
    "**/*.fdb_latexmk": true,
    "**/*.fls": true,
    "**/*.log": true,
    "**/*.synctex.gz": true
  }
}
```

### macOS Installation

```bash
brew cask install mactex-no-gui
```
