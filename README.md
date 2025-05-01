# The Mastermind behind Refinement Types
Should your function only admit positive integers? Does it always return non-empty lists?

Refinement types are wonderful: beyond typing, you can annotate the behaviour of your function values. It's a great ally for the correctness of a program, but there is fine print: obviously the wonder is not to do a check at runtime, but at compile time, and that may not be trivial.

What we need is a brain, a mastermind that takes all the conditions and validates our program. And for it to work, this mastermind has to cleverly combine many ingredients: dependent types, logic, polymorphism... a very interesting mess.

In this talk we want to present, in an intuitive way and through examples, these masterminds, the SMT (Satisfiability Modulo Theories) solvers, and the applications to the semantic enrichment of many programming languages, as is the case of Z3 solver with Liquid Haskell, and compare the approach of refinement types with that of dependent types, as happens with Idris, Agda or Lean.


