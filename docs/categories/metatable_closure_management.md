# Metatable and Closure Management

This section covers all functions related to metatable manipulation and closure handling.

## Metatable and Closure Functions

### [getrawmetatable](../examples/getrawmetatable_example.md)
Returns an object's metatable, ignoring the `__metatable` metamethod.

**Description:**
`getrawmetatable` allows access to the original metatable of an object, bypassing any restrictions that may be in place via the `__metatable` field.

**Arguments:**
- `object` *(table)*: The object whose metatable is to be retrieved.

**Returns:**
- *(table)*: The original metatable of the object.

---

### [setrawmetatable](../examples/setrawmetatable_example.md)
Sets an object's metatable, ignoring the `__metatable` metamethod.

**Description:**
`setrawmetatable` sets a new metatable for an object, even if the `__metatable` field is present, which normally prevents modification.

**Arguments:**
- `object` *(table)*: The object whose metatable is to be set.
- `metatable` *(table)*: The new metatable to assign.

**Returns:**
- *(bool)*: Returns true if the metatable was successfully set, false otherwise.

---

### [clonefunction](../examples/clonefunction_example.md)
Clones a function.

**Description:**
`clonefunction` creates an exact copy of a Lua function, which can then be used independently of the original.

**Arguments:**
- `func` *(function)*: The function to be cloned.

**Returns:**
- *(function)*: The cloned function.

---

### [newcclosure](../examples/newcclosure_example.md)
Creates a C wrapper around `closure`.

**Description:**
`newcclosure` wraps a given Lua function in a C closure, which can improve performance and security when interacting with certain systems.

**Arguments:**
- `closure` *(function)*: The Lua function to wrap.

**Returns:**
- *(function)*: The C closure wrapping the original function.

---

### [hookfunction](../examples/hookfunction_example.md)
Hooks a Lua or C function in-place. Returns a copy of the original function.

**Description:**
`hookfunction` replaces a target function with a new function, allowing custom behavior to be injected. The original function is returned for further use if needed.

**Arguments:**
- `target` *(function)*: The function to be hooked.
- `replacement` *(function)*: The function that will replace the original.

**Returns:**
- *(function)*: The original, unhooked function.

---

### [hookmetamethod](../examples/hookmetamethod_example.md)
Hooks a metatable method.

**Description:**
`hookmetamethod` allows you to replace a specific method in an object's metatable, enabling custom behavior when that method is called.

**Arguments:**
- `object` *(table)*: The object whose metatable method is to be hooked.
- `method` *(string)*: The name of the method to hook.
- `replacement` *(function)*: The function that will replace the original method.

**Returns:**
- *(function)*: The original method before it was hooked.

---

### [setreadonly](../examples/setreadonly_example.md)
Sets a table's read-only flag.

**Description:**
`setreadonly` is used to make a table read-only, preventing further modifications to its keys or values.

**Arguments:**
- `table` *(table)*: The table to modify.
- `readonly` *(bool)*: Whether the table should be set to read-only (true) or writable (false).

**Returns:**
- *(bool)*: Returns true if the operation was successful, false otherwise.

---

### [makewritable](../examples/make_writable_example.md)
Equivalent to `setreadonly(table, false)`.

**Description:**
`makewritable` is a convenience function to make a table writable, allowing modifications.

**Arguments:**
- `table` *(table)*: The table to modify.

**Returns:**
- *(bool)*: Returns true if the table was successfully made writable.

---

### [make_readonly](../examples/make_readonly_example.md)
Equivalent to `setreadonly(table, true)`.

**Description:**
`make_readonly` is a convenience function to make a table read-only.

**Arguments:**
- `table` *(table)*: The table to modify.

**Returns:**
- *(bool)*: Returns true if the table was successfully made read-only.

---

### [setscriptable](../examples/setscriptable_example.md)
Sets a property's scriptable flag.

**Description:**
`setscriptable` controls whether a property of an object can be accessed or modified by scripts.

**Arguments:**
- `object` *(Instance)*: The object whose property is to be modified.
- `property` *(string)*: The name of the property.
- `scriptable` *(bool)*: Whether the property should be scriptable (true) or not (false).

**Returns:**
- *(bool)*: Returns true if the operation was successful, false otherwise.

---

### [isscriptable](../examples/isscriptable_example.md)
Returns whether a property is scriptable.

**Description:**
`isscriptable` checks if a specific property of an object can be accessed or modified by scripts.

**Arguments:**
- `object` *(Instance)*: The object whose property is being checked.
- `property` *(string)*: The name of the property.

**Returns:**
- *(bool)*: Returns true if the property is scriptable, false otherwise.