# dotfiles说明
可以在一台新机上git clone下来这个仓库，之后写一个bash脚本，自动化地为新机的配置文件符号连接到这个仓库中的文件。(具体可以见missing semester的lab5)

## 上传与2024.7.18
swapkey.ahk是一个脚本文件，需安装autohotkey(windows)，默认位置安装即可，然后双击这个脚本文件即可实现ctrl键与capslock键互换。
而.Xmodmap是linux上的脚本文件，需sudo apt-get install x11-xserver-utils，将这个文件放在~中，之后xmodmap ~/.Xmodmap即可实现同样的效果。


## 上传于2024.7.4
有两个文件：tmux.conf，此文件的作用是修改tmux的配置文件，但只把前缀键从C-b改到C-a，如果在使用过程中某个软件需要用C-a前缀键，可以按两次C-a从而激活tmux的前缀。
vimrc，为vim编辑器的配置文件，具体修改可以见文件内的注释。

vim中的插件解释：

preservim/NERDTree:
这是一个文件系统浏览器插件。它允许您在 Vim 中查看目录结构,浏览文件,并执行基本的文件系统操作。非常有助于在不离开 Vim 的情况下管理项目文件。

ycm-core/YouCompleteMe:
这是一个强大的代码补全引擎。它支持多种编程语言,提供智能的代码补全建议,可以大大提高编码效率。它还包括一些额外的功能,如语法错误检查和定义跳转。

plasticboy/vim-markdown:
这个插件增强了 Vim 对 Markdown 文件的支持。它提供语法高亮、折叠、快捷键等功能,使编辑 Markdown 文件变得更加方便。

tpope/vim-commentary:
这是一个注释插件。它提供了快速注释/取消注释代码的功能,支持多种编程语言。通过简单的快捷键,您可以轻松地注释或取消注释单行或多行代码。您可以轻松地注释或取消注释单行或多行代码。
