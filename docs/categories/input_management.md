# Input Management

This section covers all functions related to managing keyboard and mouse inputs.

## Keyboard and Mouse Functions

### [keypress](../examples/keypress_example.md)
Simulates a key press for the specified KeyCode.

**Description:**
`keypress` sends an input signal to simulate pressing down a key on the keyboard.

**Arguments:**
- `keycode` *(string)*: The code of the key to be pressed.

**Returns:**
- *(bool)*: Returns true if the key press was successfully simulated.

---

### [keyrelease](../examples/KeyRelease_example.md)
Simulates a key release for the specified KeyCode.

**Description:**
`keyrelease` sends an input signal to simulate releasing a key on the keyboard.

**Arguments:**
- `keycode` *(string)*: The code of the key to be released.

**Returns:**
- *(bool)*: Returns true if the key release was successfully simulated.

---

### [KeyRelease](../examples/KeyRelease_example.md)
Simulates a key release.

**Description:**
`KeyRelease` is used to simulate releasing a specific key on the keyboard.

**Arguments:**
- `keycode` *(string)*: The key code to be released.

**Returns:**
- *(bool)*: Returns true if the key release was successfully simulated.

---

### [MouseMoveAbs](../examples/MouseMoveAbs_example.md)
Moves the mouse to the specified absolute coordinates.

**Description:**
`MouseMoveAbs` sets the mouse position to specific absolute screen coordinates.

**Arguments:**
- `x` *(number)*: The X coordinate to move the mouse to.
- `y` *(number)*: The Y coordinate to move the mouse to.

**Returns:**
- *(bool)*: Returns true if the mouse movement was successful.

---

### [MouseMoveRel](../examples/MouseMoveRel_example.md)
Moves the mouse relative to its current position.

**Description:**
`MouseMoveRel` moves the mouse by a specified offset relative to its current position.

**Arguments:**
- `dx` *(number)*: The change in X position.
- `dy` *(number)*: The change in Y position.

**Returns:**
- *(bool)*: Returns true if the mouse movement was successful.

---

### [mouse1click](../examples/mouse1click_example.md)
Simulates a left mouse click at the current mouse position.

**Description:**
`mouse1click` sends an input signal to simulate a left mouse button click.

**Returns:**
- *(bool)*: Returns true if the mouse click was successfully simulated.

---

### [mouse2click](../examples/mouse2click_example.md)
Simulates a right mouse click at the current mouse position.

**Description:**
`mouse2click` sends an input signal to simulate a right mouse button click.

**Returns:**
- *(bool)*: Returns true if the mouse click was successfully simulated.

---

### [Mouse1Press](../examples/Mouse1Press_example.md)
Simulates a left mouse button press.

**Description:**
`Mouse1Press` simulates pressing the left mouse button without releasing it.

**Returns:**
- *(bool)*: Returns true if the mouse button press was successful.

---

### [Mouse2Press](../examples/Mouse2Press_example.md)
Simulates a right mouse button press.

**Description:**
`Mouse2Press` simulates pressing the right mouse button without releasing it.

**Returns:**
- *(bool)*: Returns true if the mouse button press was successful.

---

### [Mouse1Release](../examples/Mouse1Release_example.md)
Simulates a left mouse button release.

**Description:**
`Mouse1Release` simulates releasing the left mouse button.

**Returns:**
- *(bool)*: Returns true if the mouse button release was successful.

---

### [Mouse2Release](../examples/Mouse2Release_example.md)
Simulates a right mouse button release.

**Description:**
`Mouse2Release` simulates releasing the right mouse button.

**Returns:**
- *(bool)*: Returns true if the mouse button release was successful.

---

### [MouseScroll](../examples/mousescroll_example.md)
Simulates a scroll event.

**Description:**
`MouseScroll` simulates scrolling the mouse wheel forward or backward.

**Arguments:**
- `direction` *(string)*: The direction to scroll, either "up" or "down".

**Returns:**
- *(bool)*: Returns true if the scroll was successful.

### [mousemoverel](../examples/MouseMoveRel_example.md)
Moves the mouse relative to its current position.

**Description:**
`mousemoverel` moves the mouse by a specified offset relative to its current position.

**Arguments:**
- `dx` *(number)*: The change in X position.
- `dy` *(number)*: The change in Y position.

**Returns:**
- *(bool)*: Returns true if the mouse movement was successful.

---

### [mousemoveabs](../examples/MouseMoveAbs_example.md)
Moves the mouse to the specified coordinates.

**Description:**
`mousemoveabs` sets the mouse position to specific screen coordinates.

**Arguments:**
- `x` *(number)*: The X coordinate to move the mouse to.
- `y` *(number)*: The Y coordinate to move the mouse to.

**Returns:**
- *(bool)*: Returns true if the mouse movement was successful.