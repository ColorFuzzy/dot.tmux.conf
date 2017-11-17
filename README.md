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
