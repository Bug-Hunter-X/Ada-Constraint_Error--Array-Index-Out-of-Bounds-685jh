# Ada Constraint_Error Example

This repository demonstrates a common error in Ada programming: accessing an array element outside of its declared bounds.  This leads to a `Constraint_Error` exception.

The `bug.ada` file contains code that attempts to access an element beyond the array's defined range. The `bugSolution.ada` file provides a corrected version that handles potential index errors.

## Running the Code

You will need an Ada compiler (like GNAT) to compile and run the code.  Compilation and execution instructions will vary based on your compiler and operating system. Consult the documentation for your specific compiler for details.  Generally, compilation would involve a command similar to:

```bash
gnatmake bug.ada
```