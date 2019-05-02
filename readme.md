#### setup
```
git clone https://github.com/wilmoore/.tmux ~/.config/tmux
ln -fs ~/.config/tmux/tmux.conf ~/.tmux.conf
TERM=xterm-256color tmux
```

or

```
TERM=xterm-256color tmux -f $XDG_CONFIG_HOME/tmux/tmux.conf
```

#### To view installed tmux version number:

```
tmux -V
```
