<div align=center>
</div>

```lua
function ts(y)
    print(y)
    local a = y
    local b = a
    local c = b
    local d = c
    local e = d
    local f = e
    local g = f
    local h = g
    local i = h
    local j = i
    local k = j
    local l = k
    return l
end

local one = ts(ts(ts(ts(ts(ts(ts(ts(ts(ts(ts(ts(ts("Hi?")))))))))))))
local two = ts(ts(ts(ts(ts(ts(ts(ts(one)))))))))
local three = ts(ts(ts(ts(ts(ts(ts(two))))))))
local four = ts(ts(ts(ts(three)))))
ts(four)
```
