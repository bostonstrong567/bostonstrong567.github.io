# getgc

**Description:**

This function demonstrates the usage of the getgc API.

**Example:**

```lua
-- Get all garbage collected objects
local gc_objects = getgc()

for _, obj in ipairs(gc_objects) do
    print(obj)
end
```
