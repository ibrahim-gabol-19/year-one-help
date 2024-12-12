
- Scope: The block or blocks of code in which a function or variable can be accessed

- Lifetime: The time period during which a function or variable can be used

- #define: A pre-processor keyword used to indicate that this line is a macro definition.Used to make code easier to read, maintain and change

- #include: A way of including externally defined functions and constants by the pre-processor.

- Segmentation fault: This occurs when a program attempts to access a page and the request could not be completed.

- Pointer Arithmetic: The use of arithmetic operators on the address value to obtain known memory addresses from a given point

- Linking: Method of combining multiple object files into a single executable.

- Imperative programming: The type of programming that follows a series of statements to achieve an outcome.

- Escape character: Special character used to force an alternate interpretation of the following character. It is typically "" although others exist

- Pointer: A variable that contains a memory address

- Heap: A part of the computer memory that uses malloc and free to allocate and remove memory respectively

- Struct: A user define data type that can internally hold multiple types of data

- Compound statement: A block of statements wrapped by a pair of curly brackets

- Dereference: To retrieve the value stored at the address of a pointer using the \* operator

- Free: When allocating memory to the heap, calling free will mark the memory segment as no longer needed

- Abstraction: A technique for managing complexity of computer systems by establishing a level of complexity, suppressing more complex details below the current level.

- Case Expression: An expression that must be evaluated to an integral or enumerated type that is used in switch blocks

- GCC COMPILATION PROCESS:

- C Source Files are sent to the Pre-Processor
    
- The Pre-Processor handles #include and #define
    
- Then Object file .0 contains the binary code compiled from the source file
    
- Then Linker combines object files into single executable program
    

- Resolves addresses of function and variables

- VIRTUAL MEMORY:

- Memory management technique that allows programs to access more memory than is physically available. Memory is divided into pages (segments) A Memory Management Unit (MMU) maps virtual addresses to physical addresses. - a virtual page is allocated to a physical page Processes have to be mapped into physical memory to run. But there can be many more virtual pages than available physical pages.

- Pages not currently needed can be swapped to disk - And reloaded when needed.

- Static:

- A static variable inside a function keeps its value between invocations.

- A static global variable or a function is "seen" only in the file it's declared in
