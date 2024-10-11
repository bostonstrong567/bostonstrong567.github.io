# loadfile

**Description:**

This function demonstrates the usage of the loadfile API.

**Example:**

```lua
-- Load a Lua script from a file
local chunk = loadfile('somefile.lua')

if chunk then
    chunk()
else
    print("Failed to load file")
end
```
