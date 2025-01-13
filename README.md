# Simple Scripting Language Interpreter Pink



## Features

This project covers essential concepts of compiler and interpreter design, including:

- **Lexical Analysis**: Tokenizing source code into meaningful symbols.
- **Syntax Analysis**: Validating the structure of the language using parsing techniques.
- **Parsing Algorithms**: Implementing algorithms to build a structured representation of the code.
- **Intermediate Representation (AST)**: Creating an Abstract Syntax Tree to represent the source code.
- **Formal Languages & Grammars**: Exploring the foundations of language design.
- **BNF Notation & Syntax Diagrams**: Using Backus-Naur Form to define the language's grammar.
- **Error Handling**: Identifying and reporting syntax and semantic errors.
- **Code Generation**: Translating the AST into executable instructions.
- **Virtual Machine (VM)**: Writing a custom virtual machine to execute the generated code.
- **Opcode Emission**: Defining and emitting opcodes and instructions for the VM.
- **Type Checking**: Ensuring type safety within the language.

## Objectives

The main goal of this project is to gain a deeper understanding of compiler and interpreter development through practical implementation. It’s a step-by-step exploration of the core components needed to create a scripting language.

## Example Code

x := 0
x := x + 1

println("The value of the global x is " + x)

if 5 ~= 2 then
  y := x + 20
  println("I have access to the local y = " + y)
  println("I have also access to the global x = " + x)
else
  x := y
  println("Error, no local variable " + y)
end

i := 1
while i <= 10 do
  println("i = " + i)
  i := i + 1
end
