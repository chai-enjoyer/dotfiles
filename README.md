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

### JetBrains Mono Nerd

```
pacman -S ttf-jetbrains-mono-nerd
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone https://github.com/chai-enjoyer/dotfiles.git .dotfiles
$ cd .dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
