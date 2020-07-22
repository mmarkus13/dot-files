# Installation:

#### [Windows]
* use GitBash or enable WSL2: https://github.com/mmarkus13/automation/blob/master/wsl_open_image_from_temrinal/wsl_enable.ps1
* install Ubuntu 20.04 LTS & Windows Terminal from Microsoft Store

#### [Linux/WSL2/Bash Terminal]
* Make sure you have vim editor installed and updated:
```
$ sudo apt-get update
$ sudo apt-get install vim
```


#### Create folder & copy repository:
```
mkdir -p ~/.vim/bundle/
cd ~/.vim/bundle/
git clone https://github.com/gmarik/Vundle.vim
```
###### ...or just directly clone it to the final destination
```
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

#### Backup your .vimrc and copy new contents from https://raw.githubusercontent.com/mmarkus13/dot-files/master/vimrc
```
mv .vimrc .vimrcBAK<date>
vi .vimrc #paste raw from Git & update to your prefrences --un/comment plugins
```

#### Install the selected (specified in .vimrc) plugins:
```
$ vim +PluginInstall +qall
```

# Plugins:
# dot-files
Dotfiles repository

## Command line tools 

### Window manager 
#### byobu
#### tmux 

## Vim - Reference

### Utilities
#### scrooloose/nerdtree
##### Use
Nerdtree can be activated by pressing Ctrl+n in Normal mode

#### majutsushi/tagbar
##### Use
Tagbar can be activated by pressing Ctrl+m in Normal mode

#### ervandew/supertab
##### Use
Automatic tab completion under Inser Mode

#### wesQ3/vim-windowswap'
##### Use 
 - Navigate to the window you'd like to move
 - Press <leader>ww
 - Navigate to the window you'd like to swap with
 - Press <leader>ww again

#### SirVer/ultisnips'
#### junegunn/fzf.vim'
#### junegunn/fzf'
#### godlygeek/tabular'
#### ctrlpvim/ctrlp.vim'
#### benmills/vimux'
#### BufOnly.vim

### Generic Programming Support 
#### jakedouglas/exuberant-ctags'
#### honza/vim-snippets'
#### Townk/vim-autoclose'
#### tomtom/tcomment_vim'
#### tobyS/vmustache'
#### janko-m/vim-test'

### Inteface Improvements
#### ryanoasis/vim-devicons'
#### vim-airline/vim-airline'
#### vim-airline/vim-airline-themes'
#### sjl/badwolf'
#### tomasr/molokai'
#### morhetz/gruvbox'
#### zenorocha/dracula-theme', {'rtp': 'vim/'}
#### junegunn/limelight.vim'
#### mkarmona/colorsbox'
#### romainl/Apprentice'
#### Lokaltog/vim-distinguished'
#### chriskempson/base16-vim'
#### w0ng/vim-hybrid'
#### AlessandroYorba/Sierra'
#### daylerees/colour-schemes'
#### effkay/argonaut.vim'

### Markdown and Writing
#### reedes/vim-pencil'
#### tpope/vim-markdown'
#### jtratner/vim-flavored-markdown'
#### LanguageTool'

### Elixir Support
#### elixir-lang/vim-elixir'
#### avdgaag/vim-phoenix'
#### mmorearty/elixir-ctags'
#### mattreduce/vim-mix'
#### BjRo/vim-extest'
#### frost/vim-eh-docs'
#### slashmili/alchemist.vim'
#### tpope/vim-endwise'
#### jadercorrea/elixir_generator.vim'

### Erlang Support
#### vim-erlang/vim-erlang-tags'
#### vim-erlang/vim-erlang-runtime'
#### vim-erlang/vim-erlang-omnicomplete'
#### vim-erlang/vim-erlang-compiler'

### ELM Support
#### lambdatoast/elm.vim'

### PHP Support
#### phpvim/phpcd.vim'
#### tobyS/pdv'

### Git Support and Integration
#### kablamo/vim-git-log'
#### gregsexton/gitv'
#### tpope/vim-fugitive'
#### jaxbot/github-issues.vim'
