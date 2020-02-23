# Dotfiles Version Control

This repo keeps configuration files and some instructions to remember useful commands.

## .spacemacs

My configuration for [Spacemacs](https://www.spacemacs.org/doc/DOCUMENTATION.html).

**Instructions**

Install (Emacs)[https://www.gnu.org/software/emacs/]

Get download the .spacemacs file and create a symbolic link in the home directory:
```bash
git clone --depth 1 https://github.com/syl20bnr/spacemacs ~/.emacs.d
git clone --depth 1 git@github.com:thspinto/dotfiles.git ~/workspace/dotfiles

ln -s ~/.spacemacs ~/workspace/dotfiles/.spacemacs
```

Shortcuts [cheatsheet](https://gist.github.com/rnwolf/e09ae9ad6d3ac759767d129d52cab1f1)
