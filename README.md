# Install

1. Vim:
    + sudo apt purge vim-tiny
    + sudo apt update
    + sudo apt install vim
    + git clone https://github.com/wirrja/vimrc.git
    + cp ./vimrc/.vimrc ~/.vimrc
2. [Vundle](https://github.com/gmarik/Vundle.vim.git)
    + git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
3. vim +PluginInstall
4. [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
   + sudo apt-get install build-essential cmake
   + sudo apt-get install python-dev python3-dev
   + cd ~/.vim/bundle/YouCompleteMe
   + ./install.py

![screenshot](vim.png)