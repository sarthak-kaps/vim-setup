# Vim Setup

This my vim setup with all the plugins and scripts.

The list of plugins is present in the `plugged` folder in the repository.
Others can be installed by adding required instructions in the `.vimrc` file.

## Requirements
* Tested on Vim version >= 8.1
* Tested on Ubuntu 18.04, 20.04 LTS

## Instructions To Install And Run

* Copy .vimrc to system .vimrc file in the root directory (if not present then create one).
  * `>$ cp vim-setup/.vimrc ~/.vimrc`
* Run vim on the shell it will download the required packages and create the `.vim` folder at the root directory.
  * `>$ vim`
* Copy the `colors` folder to the `.vim` folder 
  * `>$ cp -r vim-setup/colors .vim/colors` 

The whole setup for vim is complete.
