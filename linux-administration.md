# Linux administration

[Back home](README.md)
## Install zsh and prezto

```bash
sudo apt-get install zsh
```
* [Prezto shell - zsh based shell](https://github.com/sorin-ionescu/prezto)
In Vs Code :  [ Ctrl ] + [ Shift ] + [ p ] -> "select defaut shell" -> `/usr/bin/zsh`
* [Hyper.js - electron based terminal](https://hyper.is/)
* [Install powerline fonts for windows 10](https://medium.com/@slmeng/how-to-install-powerline-fonts-in-windows-b2eedecace58)
* [Configure Hyper for wsl](https://evdokimovm.github.io/windows/zsh/shell/syntax/highlighting/ohmyzsh/hyper/terminal/2017/02/24/how-to-install-zsh-and-oh-my-zsh-on-windows-10.html)
Change the configuration for fonts in hyper.js config
```
fontFamily: '"Ubuntu Mono derivative Powerline", DejaVu Sans Mono for Powerline, Consolas, Lucida Console, monospace',
```

## VS Code font with ligature

* Download font : https://github.com/i-tu/Hasklig/releases
settings.json
```json
    "editor.fontFamily": "Hasklig", 
    "editor.fontLigatures": true,
```
Font in terminal (to work well with powerlevel10k prompt
```json
"terminal.integrated.fontFamily": "MesloLGS NF"
```

## Know which distribution it is

```
cat /etc/issue
```

## Know which is current bash

```
ps -p $$
```

## Create user in debian

* [How to create user and add it to sudoers](https://www.digitalocean.com/community/tutorials/how-to-add-and-delete-users-on-debian-8)

