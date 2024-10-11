# getconnections

**Description:**

This function demonstrates the usage of the getconnections API.

**Example:**

```lua
-- Get all connections of an event
local connections = getconnections(some_event)

for _, connection in ipairs(connections) do
    print(connection.Function)
end
```
