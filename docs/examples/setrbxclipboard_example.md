# setrbxclipboard

**Description:**

This function demonstrates the usage of the setrbxclipboard API.

**Example:**

```lua
-- Set text to Roblox's clipboard
local success = setrbxclipboard("Some Roblox data")

if success then
    print("Successfully copied to Roblox clipboard")
else
    print("Failed to copy to Roblox clipboard")
end
```
