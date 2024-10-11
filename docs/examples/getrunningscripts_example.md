# getrunningscripts

**Description:**

This function demonstrates the usage of the getrunningscripts API.

**Example:**

```lua
-- Get all running scripts
local running_scripts = getrunningscripts()

for _, script in ipairs(running_scripts) do
    print(script)
end
```
