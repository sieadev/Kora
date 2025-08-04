# Kora

Kora is a high-performance, deeply object-oriented programming language where everything is treated as an object. No statics, no globals, and no exceptions to the object model. It’s built to run efficiently across platforms using a custom virtual machine, with optional native compilation for extra speed and portability. Kora’s design focuses on a pure object model, consistent message passing, and dynamic flexibility, all while keeping real-world use in mind. 

> **Note:** As I’m currently working on this solo, development might be slow, but I’m focused on prioritizing quality over speed.  
> -> Contributions welcome <3

---

## Key Features

- **Pure Object Model:** Everything is an object, ensuring a consistent and extensible programming experience.
- **Cross-Platform VM:** Runs on a lightweight, custom-built virtual machine designed for portability.
- **Optional Native Compilation:** For performance-critical applications, Kora can compile down to native machine code.
- **Dynamic & Flexible:** Supports dynamic message passing and reflection while maintaining high performance.
- **Minimal Syntax:** Focused on simplicity and expressiveness without sacrificing power.

---

## Roadmap

### Phase 1: Getting the Basics Right  
- Finalize Kora’s core syntax and how the language looks  
- Figure out naming rules like how files, modules, and classes should be organized  
- Decide on the type system and the basics of the object model  
- Plan out the big picture: compiler, VM, runtime & how it all fits together  
- Design the bytecode format and how the VM will run it  
- Write up a clear language spec to keep everything on track  

> **Note:** Everything beyond this point is highly hypothetical and subject to change as development progresses.

### Phase 2: Building the Core  
- Write the lexer, parser, and build the AST based on the syntax rules  
- Create the compiler to turn source code into bytecode  
- Build a simple stack-based VM to run that bytecode  
- Add primitive types with boxing/unboxing to keep things efficient  
- Get basic memory management going (like ref counting or simple GC)  
- Set up a REPL and a small standard library to play with  

### Phase 3: Making It Faster & Friendlier  
- Speed up the VM and improve error messages  
- Look into adding JIT or native compilation for extra performance  
- Grow the standard library and add tools like a package manager and formatter  
- Make sure it builds smoothly on different platforms and set up continuous testing  

### Phase 4: Adding the Cool Stuff  
- Add support for concurrency and async programming  
- Improve the garbage collector to be smarter and faster  
- Build meta-programming and reflection features  
- Create a Foreign Function Interface (FFI) so Kora can talk to C, Rust, etc.  
- Work on IDE support and language server integration  

---

## Getting Started

*Instructions for building, running, and contributing will be added soon.*

---

## Contributing

Kora is an open-source project. Contributions, bug reports, and feature requests are welcome! Please follow the contribution guidelines once they are published.

---

## License

Kora is released under the [MIT License](LICENSE).

---

Built with ❤️ for object-oriented programming — inspired by Java, Rust, and C.
