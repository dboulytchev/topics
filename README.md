### Research/practical topics (Autumn 2026)

- A debugger for LaMa programming language. This includes an accurate generation of
  debug information (DWARF) and patching GDB in order to support some constructs
  it doesn't support out of the box (in particular, closure elements).
  The work may involve extending LaMa programming language and its runtime with
  bit-operating constructs. 

- Dynamic codegeneration/staging for LaMa programming language. This involves
  saturating the language with staging constructs and modifying existing
  codegeneration pass to be called at runtime.

- ARM backend for LaMa programming language. This involves bootstrapping
  the runtime library and implementing ARM codegenerator in the same
  manner as existing x86/32/64 backend.

- Property-based testing library for LaMa. Property-based testing is an approach
  to software testing utilizing the idea of randomized checking of some
  computational invariants ("properties"), discovering the inputs
  on which the program under testing returns invalid results, and
  minimizing these inputs via "shrinking".

- (master level) Generic codegeneration with two relational interpreters.
  Devise and develop a framework for synthesising a codegenerator
  based on two relational interpreters: one for intermediate-level
  abstract machine, and another for hardware model.