# request

**Description:**

This function demonstrates the usage of the request API.

**Example:**

```lua
-- Make a web request
local response = request({ Url = "https://example.com", Method = "GET" })

if response.Success then
    print("Response: " .. response.Body)
else
    print("Request failed")
end
```
