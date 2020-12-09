# Setting up Vim
## Step 1:
#### Getting the latest version of Vim.
```
sudo add-apt-repository ppa:jonathonf/vim
sudo apt update
sudo apt install vim
```

#### To uninstall
```
sudo apt remove vim
sudo add-apt-repository --remove ppa:jonathonf/vim
```

## Step 2:
### Get a Plugin Manager like [Vundle](https://github.com/VundleVim/Vundle.vim).
1. Open a terminal and clone the Vundle repository.
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
2. Open [`~/.vimrc`](https://github.com/aneee004/getting-vim/blob/main/.vimrc) and run `:PluginInstall`.

## Step 3:
### Other dependencies:
1. Install node with `sudo apt isntall nodejs`.
