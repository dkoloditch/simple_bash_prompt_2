# simple_bash_prompt

A simple bash prompt for ruby and RVM users. Features colors and shows current folder, ruby version, gemset, and git branch.

![sexy-bash-prompt screenshot][screenshot]

[screenshot]: screenshot.png

## Install
Just copy and paste one of the following lines in your terminal.

.bashrc 
```bash
(cd $HOME && wget https://raw.githubusercontent.com/dkoloditch/simple_bash_prompt_2/master/.bash_prompt) && (echo "" >> $HOME/.bashrc && echo "source $HOME/.bash_prompt" >> $HOME/.bashrc) && source $HOME/.bashrc
```

.bash_profile (e.g. OS X)
```bash
(cd $HOME && wget https://raw.githubusercontent.com/dkoloditch/simple_bash_prompt_2/master/.bash_prompt) && (echo "" >> $HOME/.bash_profile && echo "source $HOME/.bash_prompt" >> $HOME/.bash_profile) && source $HOME/.bash_profile
```

## Uninstall
1. ```rm $HOME/.bash_prompt```
2. Open $HOME/.bashrc or $HOME/.bash_profile and remove the line "source $HOME/.bash_prompt"

Enjoy.
