# LACS Compiler

Scala is a widely known object-oriented programming language. This compiler is made for the _Lacs_ language, which is a subset of Scala. It contains most of the syntactic and semantic features as in Scala.

### Key Implementations
- Used MIPS programming to program different types of abstract code
  - basic mathematical operations
  - if statements
  - while loops
  - variable definitions
  - procedures (also known as methods/functions in other programming languages)
  - closures (First Class Values)
- Added Recognition and Maximal Munch Scanning to ensure the code meets the syntactic and semantic definitions for the Lacs Language Rules
- Added Type-Checker into the compiler, ensuring code blocks are processing and returning information of valid types
- Added the CYK Parsing algorithm for the language's Context Free Grammar
- Implemented Cheney's Garbage Collection Algorithm for heap-based allocations in the language

### Compilation

All components of the compiler have already been compiled in the project. No further compilation needed.

### Execution
`
A10.tests <br>
A11.tests
`

Please contact to view and run code (r2vasude@uwaterloo.ca or vasuraghav04@gmail.com).
