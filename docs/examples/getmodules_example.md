# getmodules

**Description:**

This function demonstrates the usage of the getmodules API.

**Example:**

```lua
-- Get all loaded modules
local modules = getmodules()

for _, module in ipairs(modules) do
    print(module)
end
```
