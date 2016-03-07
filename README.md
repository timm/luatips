# Give us this day our daily Lua tip

## And our next best tip is...

??

## Lua as shell command

Add these two lines at the top of your lua source code at the file can be executed by either lua or a unix shell.

```lua
#!/bin/sh
_=[[ exec lua "$0" "$@" ]]
print("Running", _VERSION)
print("Options", ...)
```
Source:   http://lua-users.org/lists/lua-l/2015-01/msg00633.html. 

