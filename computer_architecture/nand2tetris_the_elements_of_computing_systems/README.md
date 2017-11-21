These files can all be found at http://nand2tetris.org/chapters/

Reading the preface will likely give you an idea of what is going on here

> I'm reading nand2tetris in an effort to understand more about CS and develop a better overall understanding of engineering. I am currently looking into OS development and was finding myself running up against a lot of hurdles due to a subpar understanding of the bowels of computer architectures, for example, I started reading C++ source, came up against pointers, did some reading, cool, so you allocate memory, why? Oh but C++ handles some of it, ok, so I'll figure it out with C, but wait, why do we even have to allocate memory, in fact, wtf IS memory, on a technical level. These are the questions that drove me to Nand2tetris, I hope it will help me answer them. I also chose this particular book after looking at teachyourselfcs.com, and after seeing that it was project based and not just talk, I jumped on it. I tried Interpretation of Computer Programs but I'm not sure if I'm ready for the, "dryness" of it yet. 

## What do I intend to learn?

* Hardware: Logic gates, Boolean arithmetic, multiplexors, flip-flops, registers,
RAM units, counters, Hardware Description Language (HDL), chip simulation and
testing.
* Architecture: ALU/CPU design and implementation, machine code, assembly
language programming, addressing modes, memory-mapped input/output (I/O).
* Operating systems: Memory management, math library, basic I/O drivers,
screen management, file I/O, high-level language support.
* Programming languages: Object-based design and programming, abstract data
types, scoping rules, syntax and semantics, references.
* Compilers: Lexical analysis, top-down parsing, symbol tables, virtual stackbased
machine, code generation, implementation of arrays and objects.
* Data structures and algorithms: Stacks, hash tables, lists, recursion, arithmetic
algorithms, geometric algorithms, running time considerations.
* Software engineering: Modular design, the interface/implementation paradigm,
API design and docume

## Notes

* Computers are made up off layered abstractions, we create mental models to handle the inherent complexity of a system, and then by handling individual components, we can formulate better compound ideas with singular modules. Think of this in reality in a similar way we have computers with Screens, Hard Drives, GPUs, CPUs. We have generated individual items that can hold mental complexity via that atomic item, which we can then refer to, in conversations and technical proposals, and have other people assume certain primitives as a result of these models. 

* With computers in particular, there is something of a rabbit warren of abstraction, for example, studying a low level language such as C, you may find yourself needing to better understand system calls, which requires an understanding of OS's, but then depending on how far down you wish to understand, this will lead to the Boot Record, then the BIOS, and you realise that you have found what could potentially be viewed as circular dependencies, for example, to run the Operating System (which in many people's eyes would be to make the computer actually useful), you need software to run it, but then that software requires software, so on and so forth.

* The lowest level of abstraction inside a computer, are elementary logic gates, which can be physically represented as transistors. Transistors simply being True False boolean triggers, who can have 2 states, 0 and 1. When you hear people talking about Moores Law, this is the number of transistors that can be fit into a CPU, an effective doubling of compute power every 18 months. 

#### Boolean Expressions and Notation
* ![equation](http://latex.codecogs.com/gif.latex?xy%20%3D%20and)
* ![equation](http://latex.codecogs.com/gif.latex?x%20&plus;%20y%20%3D%20or)
* ![equation](http://latex.codecogs.com/gif.latex?%5Cbar%7Ba%7D)
