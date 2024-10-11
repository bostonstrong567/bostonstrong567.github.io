# listfiles

**Description:**

This function demonstrates the usage of the listfiles API.

**Example:**

```lua
-- List all files in a folder
local files = listfiles('folderpath')

for _, file in ipairs(files) do
    print(file)
end
```
