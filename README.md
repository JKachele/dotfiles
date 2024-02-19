# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git<br>
*Use the recurse-submodules flad to import all submodules*

```
$ git clone git@github.com:JKachele/dotfiles.git --recurse-submodules
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
