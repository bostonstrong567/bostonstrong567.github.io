# GetObjects

**Description:**

This function demonstrates the usage of the GetObjects API.

**Example:**

```lua
-- Get Roblox objects from an asset ID
local objects = GetObjects("rbxassetid://123456")

for _, obj in ipairs(objects) do
    print(obj)
end
```
