# Plang
A programming language meant to be used by machine learning algorithms. 

**How does this standard work?**

This standard uses grayscale pixel values to represent instructions and data. It is meant to be extremely low level and behave more like pseudo code. Each image is then meant to be transpiled or compiled directly to bytecode. Images should be n^2 in size. 

**Standard Definition:**

 - Formating values:
   - 0: Empty. Used to fill the rest of the image when program code is finished.
   - 255: End section. (i.e. comment, instruction, type declaration, etc.)
   - 1: Comment
   - 2: Instruction
   - 3: Data type declaration
   - 4: Data declaration
   - 5: Architecture specific
 - Instructions:
   - 0 Memory:
   - 1 Bytewise operations:
   - 2 Interupts:
   - 3 Syscalls:
 - Data type declaration:
   - 0 Memory Location:
    - 0 Stack
    - 1 Heap
    - 2 Memory Mapped Location
   - 1 Primitives:
    - 
   - 2 Custom Length:
   - 3 ID:
    - 0 Numeric ID:
     - 8 byte (64 bit) wide value used as an internal reference. 
    - 1 Character ID:
     - Null terminated char array ID for human readable code. May only use ascii characters in range of 0 to 255. 

**NOT FINALIZED**
