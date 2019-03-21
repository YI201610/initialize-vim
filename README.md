# initialize-vim
よく使うvimの初期設定

## 指示に従いgit clone

- https://github.com/VundleVim/Vundle.vim
- https://github.com/plasticboy/vim-markdown


## Pluginのパスを設定

.vimrc

```
" git repos on your local machine (i.e. when working on your own plugin)
Plugin 'file:///<home directory path>/.vim/plugin'
```


## .vimrcに追加

```
let g:vim_markdown_folding_disabled = 1
let g:vim_markdown_folding_style_pythonic = 1
```

## Pluginのインストール

vimを起動して、 `:PluginInstall` 
