# XML Tools for Visual Studio Code
[![](https://img.shields.io/badge/gitter-join_chat-1dce73.svg?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4NCjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCB4PSIwIiB5PSI1IiBmaWxsPSIjZmZmIiB3aWR0aD0iMSIgaGVpZ2h0PSI1Ii8%2BPHJlY3QgeD0iMiIgeT0iNiIgZmlsbD0iI2ZmZiIgd2lkdGg9IjEiIGhlaWdodD0iNyIvPjxyZWN0IHg9IjQiIHk9IjYiIGZpbGw9IiNmZmYiIHdpZHRoPSIxIiBoZWlnaHQ9IjciLz48cmVjdCB4PSI2IiB5PSI2IiBmaWxsPSIjZmZmIiB3aWR0aD0iMSIgaGVpZ2h0PSI0Ii8%2BPC9zdmc%2B&logoWidth=8)](https://gitter.im/vscode-xml/vscode-xml)
[![Build Status](https://travis-ci.org/DotJoshJohnson/vscode-xml.svg?branch=master)](https://travis-ci.org/DotJoshJohnson/vscode-xml)

## Features
* [XML Formatting](https://github.com/DotJoshJohnson/vscode-xml/wiki/xml-formatting)
* [XML Tree View](https://github.com/DotJoshJohnson/vscode-xml/wiki/xml-tree-view)
* [XPath Evaluation](https://github.com/DotJoshJohnson/vscode-xml/wiki/xpath-evaluation)
* [XQuery Linting](https://github.com/DotJoshJohnson/vscode-xml/wiki/xquery-linting)
* [XQuery Execution](https://github.com/DotJoshJohnson/vscode-xml/wiki/xquery-script-execution)
* [XQuery Code Completion](https://github.com/DotJoshJohnson/vscode-xml/wiki/xquery-code-completion)

## Requirements
*In Progress*

## Extension Settings
* `xmlTools.enableXmlTreeView`: Enables the XML Tree View for XML documents.
* `xmlTools.ignoreDefaultNamespace`: Ignore default xmlns attributes when evaluating XPath.
* `xmlTools.persistXPathQuery`: Remember the last XPath query used.
* `xmlTools.removeCommentsOnMinify`: Remove XML comments during minification.
* `xmlTools.splitAttributesOnFormat`: Put each attribute on a new line when formatting XML. Overrides `xmlTools.splitXmlsOnFormat` if set to `true`. (V2 Formatter Only)
* `xmlTools.splitXmlnsOnFormat`: Put each xmlns attribute on a new line when formatting XML.
* `xmlTools.xmlFormatterImplementation`: Supported XML Formatters: `classic`, `v2`.
* `xmlTools.xqueryExecutionArguments`: Arguments to be passed to the XQuery execution engine.
* `xmlTools.xqueryExecutionEngine`: The full path to the executable to run when executing XQuery scripts.

## Known Issues
*In Progress*

## Release Notes
Detailed release notes are available [here](https://github.com/DotJoshJohnson/vscode-xml/releases).

## Issues
Run into a bug? Report it [here](https://github.com/DotJoshJohnson/vscode-xml/issues).
