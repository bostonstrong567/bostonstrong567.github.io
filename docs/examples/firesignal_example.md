# firesignal

**Description:**

This function demonstrates the usage of the firesignal API.

**Example:**

```lua
-- Fire a signal
local signal = Instance.new("BindableEvent")

-- Connect the signal to a function
signal.Event:Connect(function()
    print("Signal fired!")
end)

-- Fire the signal
firesignal(signal.Event)
```
