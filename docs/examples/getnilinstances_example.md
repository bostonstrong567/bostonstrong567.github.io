# getnilinstances

**Description:**

This function demonstrates the usage of the getnilinstances API.

**Example:**

```lua
-- Get all nil instances
local nil_instances = getnilinstances()

for _, instance in ipairs(nil_instances) do
    print(instance)
end
```
