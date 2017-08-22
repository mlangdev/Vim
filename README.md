# Vim editor

What Is Vim?

> Vim is a highly configurable text editor built to enable efficient text editing. It is > an improved version of the vi editor distributed with most UNIX systems.

> Vim is often called a "programmer's editor," and so useful for programming that many 
> consider it an entire IDE. It's not just for programmers, though. Vim is perfect for all > kinds of text editing, from composing email to editing configuration files.


## Installation
To install Vim in your Linux / Ubuntu environment

```sh
$ cd apt-get intall vim
```

For windows environment, access the link https://vim.sourceforge.io/download.php

### Commands
```sh
$ / - Search
$ :w  - Save
$ :wq - Save and exit
$ :q  - Exit
$ :q! - Exit without saving
$ :echo $HOME - Root directory
```
### Config
```sh
$ colorsscheme industy - change color scheme
$ set tabstop=2 - Spacing
$ filetype plugin indent on - identify file extension
$ syntax on - Enable syntax coloring
$ set shiftwidth=2 - Shift spacing
```
### Navigation
```sh
$ k - Navigation top
$ j - Navigation bottom
$ h - Navigation left
$ l - Navigation right
$ :value + :navigation - Navigation range
```
### Mode
```sh
$ i - Insert mode
$ esc - Normal mode
```