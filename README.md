# tmux-shortcut

## Basic

```
# create new screen
tmux

# attach to the last screen
tmux a

# show screen list
tmux ls 

# detach from screen
^B d

# create another new screen
^B a

# move to the next screen
^B n

# move to the previous screen
^B p

# vertically split the screen
^B %
```

## In Split mode

```
# switch between screens
^B o

# adjust the layout
^B space

# toggle sync mode
# create shortcut in ~/.tmux.conf: 
# bind = set -g synchronize-panes
^B =
```
