# todos

# setup on ubuntu

## install latest tmux

``` shell
wget https://github.com/tmux/tmux/releases/download/2.6/tmux-2.6.tar.gz
sudo apt-get build-dep tmux
./configure 
make
sudo make install

```

## clone to .tmux

``` shell
git clone https://github.com/ColorFuzzy/dot.tmux.conf.git ~/.tmux
ln -s ~/.tmux/tmux.conf ~/.tmux.conf

```

# basic usage

*@ == C-q*
- @?/: => help/command
- @c/n/p/w/,/0-9 => window create/next/previous/select/rename/choice
- @d/s/$/(/) =? session detach/select/rename/previous/next
- @%/" => pane vsplit/split

*help-mode*
C-s Enter n/N

*command mode*
:new -s session-name
:source-file ~/.tmux.conf 

*shell*
tmux attach
tmux source-file ~/.tmux.conf
