# getconstants

**Description:**

This function demonstrates the usage of the getconstants API.

**Example:**

```lua
-- Get all constants from a function
local constants = getconstants(some_function)

for i, constant in ipairs(constants) do
    print("Constant " .. i .. ":", constant)
end
```
