# isscriptable

**Description:**

This function demonstrates the usage of the isscriptable API.

**Example:**

```lua
-- Check if an object is scriptable
local myObject = Instance.new("Part")
local is_scriptable = isscriptable(myObject)

if is_scriptable then
    print("Object is scriptable")
else
    print("Object is not scriptable")
end
```
