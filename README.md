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
  Devise and implement a cross-module inlining transformation: save SM code in interface file,
  develop criteria for inlining, implement, evaluate. Implement a tail-call optimization. This work can
  be continued with other cross-module optimizations.

- First-class syntax extensions for LaMa.
  Devise and implement a built-in syntax extension mechanizm in LaMa which would let to
  extend the language with user-defined constructs. Reduce the built-in syntax to the core
  one and express it with the means of developed system.

- LaMa full-fledged bytecode interpreter, JIT, REPL.
  Current LaMa bytecode interpreter does not support separately compiled modules.
  The whole system of separate compilation and (dynamic?) linking for bytecode modules
  has to be devised and implemented. After interpreter implementation is completed the
  work can be continued to JIT implementation.

- miniKanren: debugger/visualizer/profiler.
  Devise and implement a tool for tracing the evaluation of relational programs in
  native relational terms. Devise ways to visualize the course of the search and
  gather various metrics: number of unifications, failed occurs checks, etc.

- miniKanren: tabling and disequality.
  Tabling is a powerful tool which allows to speed-up relational search essentially (up
  to several orders of magnitude). Alas, tabling is not always sound when dealing with
  disequality. Devise and implement ways which would let tabling and disequality 
  coexist.
 
- miniKanren: data representation. Traditional data structures for functional programming
  are often unsuitable in relational case. For example, representing sets as lists incurs
  an exponential performance degradation since one set can be represented by an exponential
  number of lists. Devise and implement data representations which would allow to
  eliminate this overhead.
  
- miniKanren: occurs check optimization.
  Occurs check provides unificaition soudness, and at the time drastically reduced the
  search performance. Devise and implement ways to reduce the impact of the occurs
  check on the performance of the search.

