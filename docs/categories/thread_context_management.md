# Thread and Context Management

This section covers all functions related to thread management and context-level handling.

## Thread and Context Functions

### [getthreadcontext](../examples/getthreadcontext_example.md)
Returns the current thread's context level.

**Description:**
`getthreadcontext` retrieves the current execution context level of the thread, which determines what actions the thread can perform within the game.

**Returns:**
- *(number)*: The context level of the current thread.

---

### [setthreadcontext](../examples/setthreadcontext_example.md)
Sets the current thread's context level.

**Description:**
`setthreadcontext` sets the execution context level for the current thread, which can elevate or limit the permissions for executing certain actions.

**Arguments:**
- `level` *(number)*: The context level to set for the thread.

**Returns:**
- *(bool)*: Returns true if the context level was successfully set.

---

### [queue_on_teleport](../examples/queueonteleport_example.md)
Queues a script to be executed after the next teleport.

**Description:**
`queue_on_teleport` allows you to schedule a script to run automatically after the player has teleported to a new server.

**Arguments:**
- `script` *(string)*: The script to be queued for execution.

**Returns:**
- *(bool)*: Returns true if the script was successfully queued.

---

### [getthreadidentity](../examples/getthreadidentity_example.md)
Returns the current thread's identity level.

**Description:**
`getthreadidentity` retrieves the identity level of the current thread, which can provide information about the permissions assigned to the thread.

**Returns:**
- *(number)*: The identity level of the current thread.

---

### [setidentity](../examples/setidentity_example.md)
Sets the thread identity.

**Description:**
`setidentity` changes the identity level of the thread, which controls the permissions for interacting with certain game components.

**Arguments:**
- `level` *(number)*: The identity level to set for the thread.

**Returns:**
- *(bool)*: Returns true if the identity level was successfully set.