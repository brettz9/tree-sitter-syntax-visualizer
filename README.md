# tree-sitter-syntax-visualizer
This package allows for exploring [tree-sitter](https://github.com/tree-sitter/tree-sitter)
syntax trees. This can be useful either educationally, or when developing either a
package that uses the `tree-sitter` AST or a `tree-sitter` language itself.

![screenshot](https://user-images.githubusercontent.com/3392349/34460399-6c0bf040-edc1-11e7-8e74-ae444d64dd04.png)

## Features
* Collapsible AST node tree
* Highlight selected node in text editor
* Automatically select AST node for the current cursor position
* Show/Hide unnamed AST nodes

## Important note :warning:
`tree-sitter` support in Atom is currently experimental and hasn't actually
been incorporated to Atom core. In order to use this package, you will need
to build your own version of Atom based upon the pull request atom/atom#16299
by @maxbrunfeld.

## Contributing
Contributions are more than welcome! If you want to fix something or add a
feature, please:

1. Fork the repository
2. Run `npm install`
3. Make your change
4. Create a pull request
