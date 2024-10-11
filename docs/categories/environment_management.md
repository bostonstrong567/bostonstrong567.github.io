# Environment and Script Management

This section covers all functions related to environment and script management.

## Environment Functions

### [getgenv](../examples/getgenv_example.md)
Returns Seliware's global environment table.

**Description:**
`getgenv` allows you to access and modify the global environment table.

**Returns:**
- *(table)*: The global environment table.

---

### [getrenv](../examples/getrenv_example.md)
Returns the game's global environment table.

**Description:**
`getrenv` provides access to the game's global environment, allowing inspection and modifications that affect game-specific variables and settings.

**Returns:**
- *(table)*: The game's global environment table.

---

### [getnilinstances](../examples/getnilinstances_example.md)
Returns a list of all nil-parented instances referenced by Lua.

**Description:**
`getnilinstances` retrieves instances that are no longer parented, but are still referenced, which can help with tracking hidden or unexpected game objects.

**Returns:**
- *(table)*: A list of nil-parented instances.

---

### [getloadedmodules](../examples/getloadedmodules_example.md)
Returns a list of all loaded `ModuleScript`s.

**Description:**
`getloadedmodules` lists all `ModuleScript` instances that have been loaded into the environment.

**Returns:**
- *(table)*: A list of loaded `ModuleScript` instances.

---

### [getscripts](../examples/getscripts_example.md)
Returns a list of all loaded scripts.

**Description:**
`getscripts` provides a list of all currently loaded Lua scripts, useful for understanding what scripts are active.

**Returns:**
- *(table)*: A list of loaded Lua scripts.

---

### [getinstances](../examples/getinstances_example.md)
Returns a list of all instances referenced by Lua.

**Description:**
`getinstances` allows access to all instances currently referenced in the Lua environment, including objects that may not be present in the DataModel.

**Returns:**
- *(table)*: A list of referenced instances.

---

### [getsenv](../examples/getsenv_example.md)
Returns the Lua environment associated with the main function of `script`.

**Description:**
`getsenv` is used to get the environment of a specific script, allowing access to its local variables and functions.

**Arguments:**
- `script` *(Script)*: The script whose environment is to be accessed.

**Returns:**
- *(table)*: The environment table associated with the script.

---

## Script Functions

### [getscriptfunction](../examples/getscriptfunction_example.md)
Returns the main function associated with `script`.

**Description:**
`getscriptfunction` retrieves the main function from a given script, allowing you to examine its behavior and logic.

**Arguments:**
- `script` *(Script)*: The script to retrieve the function from.

**Returns:**
- *(function)*: The main function of the script.

---

### [getscriptclosure](../examples/getscriptclosure_example.md)
Returns the closure of a script.

**Description:**
`getscriptclosure` provides the closure (function environment) of a specific script, enabling deeper access to its internal logic.

**Arguments:**
- `script` *(Script)*: The script to retrieve the closure from.

**Returns:**
- *(function)*: The closure of the script.

---

### [getscriptbytecode](../examples/getscriptbytecode_example.md)
Returns the bytecode of a script.

**Description:**
`getscriptbytecode` retrieves the raw bytecode of a given Lua script, which can be useful for analyzing or modifying the script at a low level.

**Arguments:**
- `script` *(Script)*: The script to retrieve the bytecode from.

**Returns:**
- *(string)*: The bytecode of the script.

---

### [require](../examples/require_example.md)
Allows for requiring game modules from higher contexts of script execution.

**Description:**
`require` is used to load a module script within a higher execution context, enabling the use of functions and variables defined within the module.

**Arguments:**
- `module` *(ModuleScript)*: The module script to require.

**Returns:**
- *(varies)*: The result of the module script's execution.

---

### [loadstring](../examples/loadstring_example.md)
Equivalent to Lua 5.1's `loadstring`.

**Description:**
`loadstring` dynamically compiles a string into a Lua function. This is useful for executing arbitrary code at runtime.

**Arguments:**
- `code` *(string)*: The Lua code to compile and execute.

**Returns:**
- *(function)*: The compiled function, or an error message if compilation fails.