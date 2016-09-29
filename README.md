Zenburn 256 color scheme for the color GNU ls utility.
-------------------------------------------------

Install
-------

1. Copy or link `dircolors` file to `~/.dircolors`
2. Put something like this in your shell resource file: `eval $( dircolors -b $HOME/.dircolors )`
3. To use the colors add the `--color` switch to the invocation of LS or DIR.

Example
-------

Add the following three lines to your `~/.bashrc` or `~/.zshrc` file:

    eval $( dircolors -b $HOME/.dircolors )
    alias dir='dir --color'
    alias ls='ls --color'

Screenshot
----------

![screenshot](https://github.com/agkozak/dircolors-zenburn/raw/master/img/screenshot.png)
