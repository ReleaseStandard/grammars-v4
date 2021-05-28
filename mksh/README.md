# Mksh Grammar

An ANTLR4 grammar for Mksh based on [The Mksh Programming Manual](https://linux.die.net/man/1/mksh).

## How to use

* Generate lexer and parser with ANTLR4 generator
* Include both generated and base classes to project from corresponding
  directory (C#, Java, or Go). For Go runtime you should add prefix `p.` to
  all semantic predicates, i.e: `lineTerminatorAhead` -> `p.lineTerminatorAhead()`
  and so on.

## Main contributors

* ReleaseStandard
    * Initial version

## License

[BSD-3](https://opensource.org/licenses/BSD-3-Clause)
