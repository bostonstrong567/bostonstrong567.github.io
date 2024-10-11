# WebSocket

**Description:**

This function demonstrates the usage of the WebSocket API.

**Example:**

```lua
-- Connect to a WebSocket
local ws = WebSocket.connect('wss://example.com')

ws.OnMessage:Connect(function(msg)
    print("Received message:", msg)
end)
```
