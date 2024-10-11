# getprotos

**Description:**

This function demonstrates the usage of the getprotos API.

**Example:**

```lua
-- Get all protos of a function
local protos = getprotos(some_function)

for i, proto in ipairs(protos) do
    print("Proto " .. i .. ":", proto)
end
```
