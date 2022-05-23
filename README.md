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

**NOT FINALIZED**
