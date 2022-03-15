# Implementing a Keyboard Remapping DSL in Rust Using Procedural Macros

Many technology enthusiasts will be familiar with some of the more advanced
keyboard behaviors enabled by open source firmware like QMK (Quantum Mechanical
Keyboard) for mechanical keyboards. These are really useful, but what if all
you have is an un-modifiable commodity keyboard? This is where software
keyboard remappers come in. There are a variety but this talk focuses on a Rust
implementation called qsk (Quantum Soft Keyboard).

Most rust programmers will be familiar with the use of, if not how to write,
macros. Macros in Rust come in two flavors -- declarative (aka "by example")
and procedural (aka "proc macro"). Both enable compile-time code generation
that can greatly simplify program structure by reducing repetitive code.

This session will introduce Rust macros, including the difference between
declarative and procedural, then zoom in on their use in qsk to define a
concise keyboard remapping DSL with a focus on best practices for proc macro
code structure and testing. This session draws from resources such as proc
macro crates and a community blog post that provides a simple framework for
thinking about proc macros. On top of these, Wayne will present some of his own
suggestions to take proc macro code structure and testing to the next level. 
