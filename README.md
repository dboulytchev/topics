### Research topics (Autumn 2024)

- miniKanren in LaMa.
  Implement a complete miniKanren in LaMa. This would give the following advantages:
  
  - Simplified reification/visualization
  - miniKanren REPL

  Challenges:

  - First-class tags
  - Optimizations (attributed variables, etc.)
  - Advanced features: disequality, tabling, fair conjunction, wildcard variables, etc.
  
- Cross-module inline for LaMa.
  Devise and implement a cross-module inlining transformation: sava SM code in interface file,
  develop criteria for inlining, evaluate. Implement a tail-call optimization. This work can
  be continued by other cross-module optimizations.

- First-class syntax extensions for LaMa.
  Devise and implement a built-in syntax extension mechanizm in LaMa which would let to
  extend the language with user-defined constructs. Reduce the built-in syntax to the core
  one and express it with the means of developed system.

- LaMa full-fledged bytecode interpreter, JIT, REPL.
  Current LaMa bytecode interpreter does not support separately compiled modules.
  The whole system of separate compilation and (dynamic?) linking for bytecode modules
  has to be devised and implemented. After interpreter implementation is completed the
  work can be continued to JIT implementation.

