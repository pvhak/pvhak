<div align=center>
</div>

```lua
function ts(y)
    print(y)
    local a = y
    local b = a
    local c = b
    return c
end

local one = ts(ts(ts(ts(ts(ts(ts("Hi?")))))))
local two = ts(ts(ts(one)))
local three = ts(ts(ts(ts(ts(two)))))
ts(three)
```
