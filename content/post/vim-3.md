+++
title = "VIM Part 3"
date = "2017-10-23"
tags = [
  "Vim",
  "Environment",
  "Development",
]
categories = [
  "Editors",
  "Development",
]
+++

# Configuration #

All of the vim configuration is done in a single file. For nvim this is the
`init.vim` which can be found in the nvim directory. For linux the user nvim
directory can be found at `~/.config/nvim/`. For vim the configuration file is
`.vimrc` and can be placed in the home directory. Everything that we will do
will be placed in the corisponding config file for your version of vim.

A very basic config file is represented bellow. We will go into further detail
about each part of it.
```vim
set shell=/bin/bash
set encoding=utf-8
set laststatus=2

set tabstop=8
set softtabstop=0
set shiftwidth=2
set expandtab
set smarttab
```
Lets go through this code line by line. The first line.
```vim
set shell=/bin/bash
```
This is a safty measure. Vim does not run well if you are using a non-standard
shell, like `fish`, or `zsh`. This will set the shell to use `bash`. It is
purly a precaution.
```vim
set encoding=utf-8
```
This line sets the encoding that vim will use as an output. Setting it to
utf-8. 
```vim
set laststatus=2
```
This sets the vim status line to be on always. The status line is the bar at
the bottom of the window, which shows the current file, and the mode. This will
become more useful, as we add more configuration.
