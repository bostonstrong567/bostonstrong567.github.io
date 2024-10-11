# File and Folder Management

This section covers all functions related to file and folder operations.

## File and Folder Operations

### [makefolder](../examples/makefolder_example.md)
Recursively creates directories. Returns true on success.

**Description:**
`makefolder` creates a folder at the specified path, including any necessary parent directories that do not already exist.

**Arguments:**
- `path` *(string)*: The path where the folder should be created.

**Returns:**
- *(bool)*: Returns true if the folder was successfully created, false otherwise.

---

### [delfile](../examples/delfile_example.md)
Deletes a file.

**Description:**
`delfile` removes the specified file from the file system.

**Arguments:**
- `path` *(string)*: The path to the file to be deleted.

**Returns:**
- *(bool)*: Returns true if the file was successfully deleted, false otherwise.

---

### [delfolder](../examples/delfolder_example.md)
Deletes a folder.

**Description:**
`delfolder` removes the specified folder and all its contents from the file system.

**Arguments:**
- `path` *(string)*: The path to the folder to be deleted.

**Returns:**
- *(bool)*: Returns true if the folder was successfully deleted, false otherwise.

---

### [readfile](../examples/readfile_example.md)
Reads a file from the workspace folder.

**Description:**
`readfile` opens the specified file and returns its contents as a string.

**Arguments:**
- `path` *(string)*: The path to the file to be read.

**Returns:**
- *(string)*: The contents of the file, or an error message if the file could not be read.

---

### [writefile](../examples/writefile_example.md)
Writes to a file in the workspace folder.

**Description:**
`writefile` creates or overwrites a file at the specified path with the provided content.

**Arguments:**
- `path` *(string)*: The path where the file should be written.
- `content` *(string)*: The content to be written to the file.

**Returns:**
- *(bool)*: Returns true if the file was successfully written, false otherwise.

---

### [appendfile](../examples/appendfile_example.md)
Appends to a file in the workspace folder.

**Description:**
`appendfile` adds content to the end of an existing file without overwriting its current contents.

**Arguments:**
- `path` *(string)*: The path to the file to append to.
- `content` *(string)*: The content to append to the file.

**Returns:**
- *(bool)*: Returns true if the content was successfully appended, false otherwise.

---

### [listfiles](../examples/listfiles_example.md)
Returns an array of file names belonging to a folder.

**Description:**
`listfiles` retrieves the names of all files contained in the specified directory.

**Arguments:**
- `path` *(string)*: The path of the directory to list.

**Returns:**
- *(table)*: A list of file names within the specified directory.

---

### [isfile](../examples/isfile_example.md)
Returns true if the path refers to a file.

**Description:**
`isfile` checks if the given path points to a file.

**Arguments:**
- `path` *(string)*: The path to be checked.

**Returns:**
- *(bool)*: Returns true if the path refers to a file, false otherwise.

---

### [isfolder](../examples/isfolder_example.md)
Returns true if the path refers to a folder.

**Description:**
`isfolder` checks if the given path points to a folder.

**Arguments:**
- `path` *(string)*: The path to be checked.

**Returns:**
- *(bool)*: Returns true if the path refers to a folder, false otherwise.

---

### [loadfile](../examples/loadfile_example.md)
Equivalent to `loadstring(readfile(path))`.

**Description:**
`loadfile` reads the contents of a file and compiles it as a Lua function, similar to how `loadstring` works.

**Arguments:**
- `path` *(string)*: The path to the file to be loaded.

**Returns:**
- *(function)*: The compiled function from the file's contents, or an error message if compilation fails.