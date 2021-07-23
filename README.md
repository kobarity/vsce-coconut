# Deprecated

This extension is no longer maintained as all of its features are now included in the official [Sublime Coconut](https://github.com/evhub/sublime-coconut). Please install the [Coconut (Official)](https://marketplace.visualstudio.com/items?itemName=evhub.coconut) extension.

# Coconut language support for Visual Studio Code

A basic [Coconut language](https://github.com/evhub/coconut) support for [Visual Studio Code](https://code.visualstudio.com/), based on [Sublime Coconut](https://github.com/evhub/sublime-coconut).

## Features

- Syntax highlighting for:
  - files with Coconut extensions.
  - files with Coconut shebang.
  - Coconut language fenced code block in Markdown.
- Snippet completion.
- Bracket matching/autoclosing/autosurrounding.
- Comment toggling.
- Auto indentation.
- Folding.

## Release Notes

### 1.0.0

Initial release.

### 1.0.1

Fix Markdown fenced code block grammar injection.

### 1.0.2

Fix scope names of Markdown fenced code blocks language and attributes.
Deprecate.

## Contributing

Please [open a new issue](https://github.com/kobarity/vsce-coconut/issues/new) if you find a problem. Pull requests are also welcome.

## Licenses

Copyright (C) 2021 kobarity

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program, most likely a file in the root directory, called 'LICENSE'. If not, see http://www.gnu.org/licenses.

## Credits

`syntaxes/Coconut.tmLanguage` is copied from [Sublime Coconut](https://github.com/evhub/sublime-coconut).

`syntaxes/codeblock.json` is based on [VSCode Markdown Fenced Code Block Grammar Injection Example](https://github.com/mjbvz/vscode-fenced-code-block-grammar-injection-example).

`language-configuration.json` is based on the basic [Python language](https://www.python.org/) support for [Visual Studio Code](https://code.visualstudio.com/).
