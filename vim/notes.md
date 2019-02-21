# VIM

## Open NERDTree
```
:NERDTreeFocus
```

## Creating a File or a Directory / Folder
```
:NERDTreeFocus
```
Then when in the tree view, type `m`

### File
Type `a` to add a child node

### Directory
Type `a` to add a child node and add a `/` AFTER the filename to create a directory

## Multiple Windows
- :e filename      - edit another file
- :split filename  - split window and load another file
- ctrl-w up arrow  - move cursor up a window
- ctrl-w ctrl-w    - move cursor to another window (cycle)
- ctrl-w_          - maximize current window
- ctrl-w=          - make all equal size
- 10 ctrl-w+       - increase window size by 10 lines
- :vsplit file     - vertical split
- :sview file      - same as split, but readonly
- :hide            - close current window
- :only            - keep only this window open
- :ls              - show current buffers
- :b 2             - open buffer #2 in this window

## Switching between panes
```
Ctrl +W
```
then after that, type:
```
RIGHT or LEFT arrow keys to go right or left
```

## Resize split panes
In the current pane you want to resize:
```
Ctrl + W
```
then after that, type:
```
> // Resize to the right (Hold Shift with > to use literal character of '>')
< // Resize to the left (Hold Shift with > to use literal character of '<')
+ // Resize up (Hold Shift with > to use literal character of '+')
- // Resize down (Hold Shift with > to use literal character of '-')
```
