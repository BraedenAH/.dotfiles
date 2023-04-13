# My Dotfiles
These are my dotfile configuration files for different software in Bash.
## .vimrc
This is my custom .vimrc configuration for Vim.
## .bashrc
This is my custom .bashrc configuration for Bash
## Bin
This is my repository, this houses the "linux.sh" and "cleanup.sh" scripts.
The linux script makes sure that the current os is Linux, that creates the trash directory, renames the .vimrc file to '.bup_vimrc', and then it copies the output of a vimrc override file in to the new .vim, then it adds the 'source ~/.dotfiles/etc/bash_custom' to the end of the .bashrc file in my home directory.
## Etc
This is my directory that houses two files that setup alieases and my personal vimrc settings to be overwritten on to the files responsible for my customization settings.
## Makefile
This Makefile runs the two lines "Linux" and "Clean" which run their corresponding scripts with Linux have a dependency on Clean.
