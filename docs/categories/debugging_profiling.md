# Debugging and Profiling

This section covers all functions related to debugging and profiling.

## Debugging and Profiling Functions

### [debug](../examples/debug_example.md)
Accesses Lua's debug library.

**Description:**
`debug` is used to access and manipulate the Lua debug library, providing inspection and control of the execution environment.

**Returns:**
- *(table)*: The Lua debug library.

---

### [getinfo](../examples/getinfo_example.md)
Returns information about a function or thread.

**Description:**
`getinfo` retrieves information about the stack, allowing for introspection of functions or threads.

**Arguments:**
- `func` *(function)*: The function or thread to retrieve information about.

**Returns:**
- *(table)*: Information about the function or thread.

---

### [decompile](../examples/decompile_example.md)
Decompiles `target` asynchronously.

**Description:**
`decompile` generates a human-readable version of the given compiled Lua function.

**Arguments:**
- `target` *(function)*: The function to decompile.

**Returns:**
- *(string)*: The decompiled version of the function.

---

### [disassemble](../examples/disassemble_example.md)
Disassembles Lua bytecode.

**Description:**
`disassemble` converts Lua bytecode into a human-readable instruction set.

**Arguments:**
- `bytecode` *(string)*: The bytecode to disassemble.

**Returns:**
- *(string)*: The disassembled bytecode.

---

### [getstack](../examples/getstack_example.md)
Returns a traceback of the call stack.

**Description:**
`getstack` provides a snapshot of the current call stack for debugging purposes.

**Returns:**
- *(string)*: Traceback of the call stack.

---

### [getprotos](../examples/getprotos_example.md)
Returns a table of prototypes in a Lua function.

**Description:**
`getprotos` allows for the inspection of function prototypes, aiding in understanding the structure of Lua functions.

**Arguments:**
- `func` *(function)*: The function whose prototypes are to be retrieved.

**Returns:**
- *(table)*: The prototypes within the function.

---

### [getproto](../examples/getproto_example.md)
Returns the prototype at a specific index in a function.

**Description:**
`getproto` extracts a specific prototype from a Lua function, enabling low-level function analysis.

**Arguments:**
- `func` *(function)*: The function to analyze.
- `index` *(number)*: The index of the prototype to retrieve.

**Returns:**
- *(function)*: The prototype at the specified index.