# Using Tmux Like a mothr frickn G

# Reference Guides:
Medium NERDTree Guide
```
https://medium.com/usevim/nerd-tree-guide-bb22c803dcd2
```

# Sessions
## View Sessions
```
tmux ls
```

Output of above command:
```
0: 1 windows (created Tue Feb 19 11:28:52 2019) [108x37]
1: 1 windows (created Tue Feb 19 11:29:35 2019) [108x37]
```

## Attach and reuse session
```
tmux attach-session -t 1 // Number will be associated with the session you want
```


----

# Working with windows
## Preset Key Bind for All Commands
```
Ctrl + B
```
Then enter the key for the command:
```
[
```
Above example is to scroll up and down in a window.

## Starting a new session
```
tmux new
```

## Switching Windows
```
Ctrl + B
UP ARROW or DOWN ARROW
```

## Scroll in a Window:
```
[preset]
```
```
[
```
- Then use UP / DOWN arrows to scroll by line
- Use Page Up or Page Down to scroll faster

----

# VIM

## Open Directory tree
### Press `:`, then run:
```
:NERDTreeFocus
```

### OR






<!-- Emulator: iTerm2
Multiplexer: tmux
Shell: zsh
EDITOR: vim
VISUAL: vim

tmux
-- `tmux-sensible`: Some basic useful configs
-- `tpm`: plugin manager for tmux

vim
-- pathogen: plugin manager for vim
-- NERDTree: visual directory tree
-- tagbar: IDE-style ctags -->
