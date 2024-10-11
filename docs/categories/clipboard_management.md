# Clipboard Management
This section covers all functions related to clipboard management in the API.

## Clipboard Functions

### [setclipboard](../examples/setclipboard_example.md)
Copies a string, Instance, or table of Instances to the clipboard. Returns true on success.

**Description:**  
`setclipboard` allows you to programmatically copy data to the system's clipboard. This can be a string, an individual Roblox Instance, or even a table of Instances.

**Arguments:**  
- `input` *(string | Instance | table)*: The data to be copied to the clipboard.

**Returns:**  
- *(bool)*: Returns true if the data was successfully copied to the clipboard, false otherwise.

---

### [toclipboard](../examples/toclipboard_example.md)
Copies a string to the clipboard. Similar to setclipboard, but specialized for strings.

**Description:**  
`toclipboard` is a simpler function that specifically handles copying strings to the clipboard.

**Arguments:**  
- `input` *(string)*: The string to be copied to the clipboard.

**Returns:**  
- *(bool)*: Returns true if the string was successfully copied to the clipboard, false otherwise.

---

### [setrbxclipboard](../examples/setrbxclipboard_example.md)
Copies a string or Instance to Roblox's clipboard, allowing interaction between the system and Roblox assets.

**Description:**  
`setrbxclipboard` allows copying either a string or an Instance to Roblox's clipboard.

**Arguments:**  
- `input` *(string | Instance)*: The string or Instance to be copied to Roblox's clipboard.

**Returns:**  
- *(bool)*: Returns true if the data was successfully copied to Roblox's clipboard, false otherwise.

---

### [write_clipboard](../examples/write_clipboard_example.md)
Writes a string to the clipboard.

**Description:**  
`write_clipboard` is used to directly write a string into the clipboard for later retrieval.

**Arguments:**  
- `input` *(string)*: The string to be written to the clipboard.

**Returns:**  
- *(bool)*: Returns true if the string was successfully written to the clipboard, false otherwise.
