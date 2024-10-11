# setrawmetatable

**Description:**

This function demonstrates the usage of the setrawmetatable API.

**Example:**

```lua
-- Set raw metatable for a table
local myTable = {}
local newMetatable = {
    __index = function(tbl, key)
        return "Value not found"
    end
}

setrawmetatable(myTable, newMetatable)

print(myTable.someKey)  -- Should print: Value not found
```
