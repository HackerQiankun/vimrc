# vimrc
my vimrc
---
title: myvimrc
date: 2021-06-28
tags:
---

> A simple vim config for c++,markdown and someone else code

### Vundle
*** we use the Vundle plugin package for my vim.***
you can use some one else just like vim-plug ...  
you should download the Vundle into your ~/.vim/
```sh
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
and you can put this .vimrc to you root directory


### cpp_src
we use the omnicppcplete to auto complete our cpp code.  
It requires the cpp_src tags  
so you must download the cpp_src from [vim.org](https://www.vim.org/)
and ctags the cpp_src
```sh
cd cpp_src
ctags -R --sort=1 --c++-kinds=+p --fields=+iaS --extra=+q --language-force=C++
```

### Install the plugin
go into the vim and puts ":PluginInstall" and it will download and setup soon


### Install the go plugin
you should change your proxy to a cdn because the wall
and you can puts ":GoInstallBinaries" in you vim
