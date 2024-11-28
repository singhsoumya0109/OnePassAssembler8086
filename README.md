# OnePassAssembler8086

A one-pass assembler for 8086 assembly language instructions written in Python. This assembler tokenizes assembly code, processes instructions, generates binary opcodes, maintains a symbol table, and tracks final register values. The assembler also handles labels and data declarations.

---

## Features
- **One-Pass Design**: Processes the code in a single pass to improve efficiency.
- **Binary Opcode Generation**: Converts assembly instructions into binary opcode equivalents.
- **Symbol Table Management**: Stores label addresses and variable values.
- **Register Tracking**: Tracks and outputs the final values of the registers (AX, BX, CX, DX).
- **Error Handling**: Identifies common syntax and runtime errors, such as division by zero and invalid operands.

---

## File Outputs
1. **`object.txt`**: Contains the binary opcode for the input assembly code.
2. **`symboltable.txt`**: Lists labels and their addresses, as well as variable names and their values.
3. **`registers.txt`**: Shows the final values of all registers.


