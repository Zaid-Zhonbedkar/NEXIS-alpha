**NEXIS**
Nexis is an experimental systems programming language written in Rust, focused on building a modern, high-performance, AI-ready development ecosystem from scratch.

The project currently includes:

Custom Nexis syntax
Pest-based parser
AST generation
Rust code generation backend
Native executable compilation
Early compiler pipeline architecture

Example Nexis code:

set x = 5 + 3

system.out(x)

system.out("Hello Nexis")

Current compiler flow:

.nx source
    ↓
Parser
    ↓
AST
    ↓
Rust code generation
    ↓
Native executable

Planned future features:

Static type system
Sysbase build tool
Runtime & standard library
Tensor & AI-native systems
VM/JIT compilation
Nexis OS integration

Nexis is currently in early development (v0.1).
