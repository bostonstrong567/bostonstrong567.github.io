# Signal and Event Management

This section covers all functions related to signal and event handling.

## Signal and Event Functions

### [firesignal](../examples/firesignal_example.md)
Fires a signal, including engine connections.

**Description:**
`firesignal` triggers a specific signal, calling all connected listeners, including those tied to game engine events.

**Arguments:**
- `signal` *(RBXScriptSignal)*: The signal to be fired.

**Returns:**
- *(bool)*: Returns true if the signal was successfully fired.

---

### [fireproximityprompt](../examples/fireproximityprompt_example.md)
Emulates triggering a `ProximityPrompt`.

**Description:**
`fireproximityprompt` allows you to simulate interacting with a `ProximityPrompt`, which is typically activated by a player in-game.

**Arguments:**
- `prompt` *(ProximityPrompt)*: The proximity prompt to be triggered.
- `distance` *(number, optional)*: The distance from which the prompt is fired (defaults to maximum).

**Returns:**
- *(bool)*: Returns true if the prompt was successfully fired.

---

### [firetouchinterest](../examples/firetouchinterest_example.md)
Emulates a `Touched` event on `to_touch` with `part`.

**Description:**
`firetouchinterest` is used to programmatically fire a `Touched` event, emulating physical contact between two parts.

**Arguments:**
- `part` *(BasePart)*: The part initiating the touch.
- `to_touch` *(BasePart)*: The part to be touched.
- `toggle` *(number)*: Indicates whether the touch is beginning (0) or ending (1).

**Returns:**
- *(bool)*: Returns true if the touch event was successfully fired.

---

### [fireclickdetector](../examples/fireclickdetector_example.md)
Emulates clicking a `ClickDetector`.

**Description:**
`fireclickdetector` simulates a player clicking a `ClickDetector`, which is used to interact with parts in the game.

**Arguments:**
- `clickdetector` *(ClickDetector)*: The click detector to be activated.
- `distance` *(number, optional)*: The distance from which the click is fired (defaults to maximum).

**Returns:**
- *(bool)*: Returns true if the click event was successfully simulated.