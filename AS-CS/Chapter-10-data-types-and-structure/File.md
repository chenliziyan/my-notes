# File Handeling
*use of programming language to handel information in text file*
- Opening
- Reading
- Writing
- Closing
---
## Basic Syntax
1. Open File
   1. Read `OPENFILE name.txt FOR READ`
   2. Write/Create `OPENFILE name.txt FOR  WRITE`
2. Read
   1. `READFILE name.txt, line`
3. Write
   1. `WRITE name.txt, "Sarah"`
4. Check end
   1. `IF NOT EOF(name.txt) THEN`
5. Append
   1. `OPENFILE name.txt FOR APPEND`
6. Close File
   1. `CLOSEFILE name.txt`
