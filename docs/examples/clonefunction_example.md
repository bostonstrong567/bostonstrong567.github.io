# clonefunction

**Description:**

This function demonstrates the usage of the clonefunction API.

**Example:**

```lua
-- Clone an existing function
local function original_function()
    print("Original function called")
end

local new_function = clonefunction(original_function)

new_function()  -- Should print: Original function called
```
