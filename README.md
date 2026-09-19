# ISM3232 - Module 2: zsh Navigation and File Operations

## Commands Practiced

| Command        | What it does                            |
|----------------|-----------------------------------------|
| pwd            | Prints the current working directory    |
| ls             | Lists visible files and folders         |
| ls -la         | Lists all files including hidden ones   |
| [add the rest] | [your description]                      |

## AI Use Statement
I did not use AI for this lab.

## Week 3: Virtual Environments and .zshrc

Alias added to my .zshrc:
alias ll='ls -la'
alias c='clear'
alias tree2='tree -L 2'
alias py='python3'
alias gs='git status'
alias ga='git add .'
alias gcmsg='git commit -m'
alias gp='git push'
alias gl='git log --oneline'
alias rm='rm -i'
alias activate='source .venv/bin/activate'
alias mkvenv='python3 -m venv .venv'

Commands learned:
python3 -m venv .venv   #creates a new isolated virtual environment
source .venv/bin/activate   #activates the virtual environment for this session
which python   #displays the file path of the active python executable
pip list   #shows all python packages currently installed
pip install   #installs specific python packages
pip freeze   #takes a 'screenshot' of the current packages (saveable on a file)
code ~/.zshrc   #opens the zsh configuration file in vs code to edit it