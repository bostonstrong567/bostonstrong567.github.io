# Miscellaneous Functions

This section covers various functions that do not fit into other specific categories.

## Miscellaneous Functions

### [identifyexecutor](../examples/identifyexecutor_example.md)
Returns "Script Executer Name" and version string.

**Description:**
`identifyexecutor` identifies the executor being used, providing details such as its name and version.

**Returns:**
- *(string)*: The name and version of the executor.

---

### [iswindowactive](../examples/iswindowactive_example.md)
Returns true if the game window is active.

**Description:**
`iswindowactive` checks if the game window currently has focus, which can be useful for determining user attention.

**Returns:**
- *(bool)*: Returns true if the window is active, false otherwise.

---

### [lz4compress](../examples/lz4compress_example.md)
Compresses data using LZ4 compression.

**Description:**
`lz4compress` compresses the provided data using the LZ4 algorithm, making it smaller and easier to store or transfer.

**Arguments:**
- `data` *(string)*: The data to be compressed.

**Returns:**
- *(string)*: The compressed data.

---

### [lz4decompress](../examples/lz4decompress_example.md)
Decompresses LZ4 compressed data.

**Description:**
`lz4decompress` takes compressed data and restores it to its original form using LZ4 decompression.

**Arguments:**
- `data` *(string)*: The LZ4 compressed data.

**Returns:**
- *(string)*: The decompressed data.

---

### [base64_encode](../examples/base64_encode_example.md)
Encodes input in Base64.

**Description:**
`base64_encode` encodes a given string into Base64 format, which is often used for data transmission and storage.

**Arguments:**
- `input` *(string)*: The string to be encoded.

**Returns:**
- *(string)*: The Base64 encoded representation of the input.

---

### [base64_decode](../examples/base64_decode_example.md)
Decodes input from Base64.

**Description:**
`base64_decode` takes a Base64 encoded string and decodes it back to its original form.

**Arguments:**
- `input` *(string)*: The Base64 encoded string.

**Returns:**
- *(string)*: The original, decoded string.

---

### [crypt](../examples/crypt_example.md)
Provides encryption and hashing functions.

**Description:**
`crypt` provides a set of encryption and hashing utilities, which can be used to secure data.

**Arguments:**
- `operation` *(string)*: The type of operation (e.g., "encrypt", "decrypt").
- `data` *(string)*: The data to be processed.

**Returns:**
- *(string)*: The processed data after encryption or decryption.

---

### [cache](../examples/cache_example.md)
Provides caching functionality.

**Description:**
`cache` allows you to store data temporarily for quick retrieval, reducing the need to recompute or reload it.

**Arguments:**
- `key` *(string)*: The key under which the data will be cached.
- `value` *(any)*: The value to be cached.

**Returns:**
- *(bool)*: Returns true if the data was successfully cached.

---

### [Drawing](../examples/Drawing_example.md)
Accesses drawing functions for rendering GUI elements.

**Description:**
`Drawing` provides access to various functions for drawing and rendering custom graphical elements within the game window.

**Arguments:**
- `type` *(string)*: The type of drawing (e.g., "Line", "Text").

**Returns:**
- *(object)*: A drawing object with methods to manipulate the rendered elements.

---

### [compareinstances](../examples/compareinstances_example.md)
Compares two instances for equality.

**Description:**
`compareinstances` checks if two given instances are the same, which is useful for verifying object references.

**Arguments:**
- `instance1` *(Instance)*: The first instance to compare.
- `instance2` *(Instance)*: The second instance to compare.

**Returns:**
- *(bool)*: Returns true if the instances are equal, false otherwise.