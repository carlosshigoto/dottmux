&copy; Carlos Contreras
carloscontrerasc@gmail.com

Tmux configuration folders
==========================

Installation
------------

**Clone**

    git clone https://github.com/carlosshigoto/dottmux.git ~/.tmux


**Create symbolic link**

    ln -s ~/.tmux/dottmux.conf ~/.tmux.conf

Packages
--------

* [TPM](https://github.com/tmux-plugins/tpm)
* [Resurrect](https://github.com/tmux-plugins/tmux-resurrect): Save environments `Ctrl-b + Ctrl-s`, `Ctrl-b + Ctrl-r`
* [Continuum](https://github.com/tmux-plugins/tmux-continuum): Continous saving 
* [Mouse mode](https://github.com/NHDaly/tmux-better-mouse-mode): Better mouse mode for scrolling
* [Sensible](https://github.com/tmux-plugins/tmux-sensible): Tmux options
* [Copycat](https://github.com/tmux-plugins/tmux-copycat): Highlight search with `Ctrl-b + /`, `Ctrl-b + Ctrl-f`, etc. (requires tmux 2.4+)
* [Yank](https://github.com/tmux-plugins/tmux-yank): Hightlight copy tool
* [Open](https://github.com/tmux-plugins/tmux-open): Hightlight open files, folder, links, etc

Features
--------

* `Prefix` is `Ctrl-b`
* New windows a panes open in the current folder
* Open a new window in home directory `Ctrl-b + Ctrl-C`
* `glances` added to resurrect programs list
* Compatible with [FuzzyFinder](https://github.com/junegunn/fzf)
* `Ctrl-hjkl` to navigate bwtween panes
