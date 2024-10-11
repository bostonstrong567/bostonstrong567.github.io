# http

**Description:**

This function demonstrates the usage of the http API.

**Example:**

```lua
-- Make an HTTP GET request
local response = http.get("https://example.com")

if response then
    print("Response received: " .. response)
else
    print("Failed to fetch the response")
end
```
