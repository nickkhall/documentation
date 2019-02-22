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
## Cut / Copy Line(s)
- Position the cursor at the beginning of the text you want to cut/copy.
- Press v to begin character-based visual selection, or V to select whole lines, or Ctrl-v or Ctrl-q to select a block.
- Move the cursor to the end of the text to be cut/copied. While selecting text, you can perform searches and other advanced movement.
- Press d (delete) to cut, or y (yank) to copy.
- Move the cursor to the desired paste location.
- Press p to paste after the cursor, or P to paste before.
