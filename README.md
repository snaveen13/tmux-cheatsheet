# tmux basic commands

## Sessions

**Start new**

    tmux

**Start new with name**

    tmux new -s session-name
    
**Attach to current**

    tmux attach
    
**Attach to a specific session**

    tmux attach -s session-name

**Switch to another session**

    tmux switch -t session-name

**List sessions**

    tmux ls

**Detach session**

    tmux detach
    
**Kill session**    

    tmux kill-session -t session-name

## Panes split, move and toggle

Hit `ctrl+b` and select any of the below options

```
%       horizontal split
"       vertical split

o       swap panes
q       show pane numbers
x       kill pane
⍽       space - toggle between layouts
```

## Tabs

Hit `ctrl+b` and select any of the below options

```
c           new window
,           name window
w           list windows
f           find window
&           kill window
.           move window - prompted for a new number
:movew<CR>  move window to the next unused number
```
