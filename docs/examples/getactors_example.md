# getactors

**Description:**

This function demonstrates the usage of the getactors API.

**Example:**

```lua
-- Get all actors
local actors = getactors()

for _, actor in ipairs(actors) do
    print(actor:GetFullName())
end
```
