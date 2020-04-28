# vscode plugin

## Install shell command

`cmd + shift + p` + `shellcommand`

## Display Extensions command

`code --list-extensions`

`code --list-extensions > extensions.list`

## Backup command with save file

`code --list-extensions | xargs -L 1 echo code --install-extension`

## Install Backup 

`cat extensions.list |% { code --install-extension $_}`