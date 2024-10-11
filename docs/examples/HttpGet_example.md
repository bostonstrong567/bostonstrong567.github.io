# HttpGet

**Description:**

This function demonstrates the usage of the HttpGet API.

**Example:**

```lua
-- Perform an HTTP GET request
local response = HttpGet('https://example.com')

if response then
    print("Response: " .. response)
else
    print("Failed to get response")
end
```
