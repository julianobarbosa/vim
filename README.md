# vim
VIM

# put result of :map on buffer
```vim
:redir @" | silent map | redir END | new | put!
```
