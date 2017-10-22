+++
title = "VIM Part 1"
date = "2017-10-21"
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

# Introduction #

This is part one in the documentation of my experience with Vim. I have been
using Vim for a few years, and have come to be comfortable with the quirks of
the editor. In this multi-entry guide, I will guide readers through my
experience in setting up Vim. And the suggestions that I would give to
beginners so that they can jump in to using the editor.

## Why Vim ##

The first question one may ask themselves is "Why Vim?". Well here is my answer
to this question.

1. Vim is extremely configurable. If you want something out of it, there is a
   way to get Vim to work exactly as you want it to.
2. Vim is fast. As an ultra light weight editor Vim can start up in
   milliseconds. Unlike other IDE's where a fast startup time could be a few
   seconds, a slow start up time for Vim is still measured in milliseconds.
3. Vim is just an extension of Vi, which is found everywhere. Vi is in most
   base installations of Linux, meaning that knowing Vim means one can work
   on most devices, without the need for a full IDE.
4. It can be used for any language. With some configuration Vim can act as a
   complete IDE, and while most IDE's are only made for a single group of
   programming languages, Vim can be configured to work with any programming
   language you can throw at it.

# Installing #

The first step is to install Vim. There are a few options for this. One can
install `gvim`, to use the graphical interface for Vim, or one can stay with
the terminal only interface for Vim.

A second important difference is whether to go with default Vim or use the newer
NeoVim. I would recommend NeoVim. NeoVim aims to maintain Vim, with newer
features and allows a wider development base, as it accepts contributions from
users, while Vim is still only maintained by a single developer. NeoVim
provides some additional features that allow it to move ahead of Vim, and
become a new and improved tool. You can read more about it at
[NeoVim.io](https://neovim.io)

However, basic Vim is lighter weight, and has been around for longer. So it
does have some advantages over NeoVim. But not many.

## Linux ##
### Ubuntu ###
```bash
sudo apt install neovim     # For NeoVim
sudo apt install vim        # For Vim
```
### Arch ###
```bash
sudo packman -S neovim      # For NeoVim
sudo packman -S vim         # For Vim
```
### Fedora ###
```bash
dnf -y install neovim       # For NeoVim
dnf -y install vim-enhanced # For Vim
```
## Mac OS ##
```bash
brew install neovim         # For NeoVim
brew install vim            # For Vim
```
## Window ##
Windows binaries can be found either on the [NeoVim](https://neovim.io) site or
the [Vim](https://www.vim.org) site. Then follow the instructions provided with
the binaries.

# Conclusion #

Now that you have Vim installed. Its time to learn how to use it. But that will
be for the next part of this series.

[VIM Part 2](vim-2.md)
