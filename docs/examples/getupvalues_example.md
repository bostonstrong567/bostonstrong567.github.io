# getupvalues

**Description:**

This function demonstrates the usage of the getupvalues API.

**Example:**

```lua
-- Get all upvalues of a function
local upvalues = getupvalues(some_function)

for i, value in ipairs(upvalues) do
    print("Upvalue " .. i .. ":", value)
end
```
