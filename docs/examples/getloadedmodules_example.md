# getloadedmodules

**Description:**

This function demonstrates the usage of the getloadedmodules API.

**Example:**

```lua
-- Get all loaded modules
local modules = getloadedmodules()

for _, module in ipairs(modules) do
    print(module)
end
```
