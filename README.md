# Coffeescript.vim
This project adds [CoffeeScript](http://coffeescript.org/) support to the vim 
editor. It handles syntax, indenting and more. Also included is support for CoffeeScript in
Haml and HTML.


## Install with Vundle

1. Add this to your .vimrc

```
Bundle 'GEverding/vim-coffee-sciprt'
```

2. Install

```
vim +BundleInstall! +BundleClean
```

## Note 

This is based on [kchmck's](https://github.com/kchmck/vim-coffee-script) coffeescript
plugin.  It is a very good plugin, however, I didn't like the compiler part of the plugin
cause I use make & [Redo](https://github.com/apenwarr/redo) to build my projects.
