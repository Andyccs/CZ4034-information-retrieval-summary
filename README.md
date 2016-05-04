[![Build Status](https://www.sharelatex.com/github/repos/Andyccs/CZ4034-information-retrieval-summary/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/Andyccs/CZ4034-information-retrieval-summary)

# CZ4034 Information Retrieval Summary

This LaTex document is a summary of the course CZ4034 Information Retrieval, offered by School of Computer Science and Engineering, Nanyang Technological University, Singapore. 

To download this document in PDF format: 

- [latest release](https://github.com/Andyccs/CZ4034-information-retrieval-summary/releases)
- [latest build, HEAD](https://www.sharelatex.com/github/repos/Andyccs/CZ4034-information-retrieval-summary/builds/latest/output.pdf)

## Development

To load this project using Sublime Text 3:

```Shell
$ subl --project information-retrieval.sublime-project
```

If you would like to build this document from source, first you need to install TeX:

```Shell
# For ubuntu
$ sudo apt-get install texlive-full

# For Mac OX
$ brew cask install mactex
```

Once you have TeX installed, make sure that you can use `pdflatex` command in terminal. To build the document in PDF format:

```Shell
$ make
```

To automatically build the PDF while editing `.tex` file, you need to install watch-cli using `npm` first:

```Shell
$ npm install -g watch-cli
```

Then you start watching for changes:

```Shell
$ make watch
```
