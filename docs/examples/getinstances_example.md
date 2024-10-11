# getinstances

**Description:**

This function demonstrates the usage of the getinstances API.

**Example:**

```lua
-- Get all instances in the game
local instances = getinstances()

for _, instance in ipairs(instances) do
    print(instance:GetFullName())
end
```
