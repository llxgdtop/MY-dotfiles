# dotfiles说明
可以在一台新机上git clone下来这个仓库，之后写一个bash脚本，自动化地为新机的配置文件符号连接到这个仓库中的文件。(具体可以见missing semester的lab5)

## 上传与2024.7.18
swapkey.ahk是一个脚本文件，需安装autohotkey(windows)，默认位置安装即可，然后双击这个脚本文件即可实现ctrl键与capslock键互换。
而.Xmodmap是linux上的脚本文件，需sudo apt-get install x11-xserver-utils，将这个文件放在~中，之后xmodmap ~/.Xmodmap即可实现同样的效果。


## 上传于2024.7.4
有两个文件：tmux.conf，此文件的作用是修改tmux的配置文件，但只把前缀键从C-b改到C-a，如果在使用过程中某个软件需要用C-a前缀键，可以按两次C-a从而激活tmux的前缀。
vimrc，为vim编辑器的配置文件，具体修改可以见文件内的注释。
