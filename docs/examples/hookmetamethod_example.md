# hookmetamethod

**Description:**

This function demonstrates the usage of the hookmetamethod API.

**Example:**

```lua
-- Hook a metamethod
local target = {}

setmetatable(target, {
    __index = function(t, key)
        return "Original value"
    end
})

local original_method = hookmetamethod(target, "__index", function(tbl, key)
    print("Hooked __index called for key: " .. key)
    return original_method(tbl, key)
end)

print(target.someKey)
```
