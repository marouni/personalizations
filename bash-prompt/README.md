## Personal Bash prompt theme for bash-git-prompt
* Setup bash-git-prompt from https://github.com/magicmonty/bash-git-prompt
* Add the theme file to the themes folder

* Add the following to ~/.bashrc :
```
# bash git prompt from https://github.com/magicmonty/bash-git-prompt
GIT_PROMPT_ONLY_IN_REPO=0
GIT_PROMPT_THEME=Custom
GIT_PROMPT_THEME_FILE=/path/to/marouni.bgptheme
source /path/to/gitprompt.sh
```

Result :
```
┌─[✔ ]─[~/tools/personalizations/bash-prompt] [master|…3] 
└╼[00:47]─[xxx@machine]$
```
