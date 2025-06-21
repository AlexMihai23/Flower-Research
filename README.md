# Flower-Research

Memory writer/reader

Search for memory addresses without being detected. (for now atleast)

---

## Features

### v0.1

**1. Attach to process Task Manager style. (Apps and Detalied Apps)**

---

**2. Search:**
- 4 Bytes
- Float
- String
- Array of Bytes

  - Exact Value
  - Unknown Initial Value (buggy)
  - Changed Value
  - Increased Value
  - Decreased Value

---

**3. Address List:**
- Address
- Type
- Old Value
- Current Value
- Freeze (not tested)
- Context Menu on right click:
  - Copy Address
  - Copy Value
  - Copy Old Value
  - Delete Record
  - Disassembly this address
  - Memory View this address
  - Find out what access this address (not implemented yet just blank window, it has a watcher so if you use it on the game and has anti cheat it will crash the game)
  - Bookmark address
  - Highlight in scan result

---

**4. Disassembler View (very buggy)**
- Bookmark
- Address
- Bytes
- Opcode
- Comment (the code is trying to assume what is on that opcopde, for now only strings in the future 4bytes, float and hex)
- GoTo address
- Opcode explanation
- Context Menu on right click:
  - Copy address
  - Copy bytes
  - Copy Opcode
  - Copy Comment
  - Disassemble this address
  - Memory View this address

---

**5. Memory View**
- Address
- Hex Bytes
- ASCII text
- GoTo address
- Context Menu on right click:
  - Copy address
  - Copy bytes
  - Copy ASCII text

---

**6. Show Strings (implemented but forgot to call the function)**
- Show every address that contains your string (example: searched value - TheEvilAngel (player name) inside Show Strings window you can see "TheEvilAngel [ID:4207]" because contains your searched value)
- Context Menu on right click:
  - Copy Address
  - Copy String
  - Disassembly this address
  - Memory View this address

---

**7. Others:**
- Switch Theme button (Dark/Light)
- Refresh Address List button (manual refresh just in case)
- Add to address list button (just an arrow pointing down)
- Memory Viewer button
- Disassembler View button
- Show Strings button
- Feedback text

---

## Upcoming:
- Find out what access this address
- Ultimap
- Data structures
- Alot of bug fix and optimization.
