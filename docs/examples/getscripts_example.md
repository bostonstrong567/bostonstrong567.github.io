# getscripts

**Description:**

This function demonstrates the usage of the getscripts API.

**Example:**

```lua
-- Get all scripts
local scripts = getscripts()

for _, script in ipairs(scripts) do
    print(script:GetFullName())
end
```
