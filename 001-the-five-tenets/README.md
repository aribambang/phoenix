# The Five Tenets of Functional Programming

## The functional paradigm

0. Computing problems consist of data and behavior

   - synonyms: state and operations; objects and methods; verbs and methods

1. Immutability of data/state

   - once a variable is assigned to value, it should not be re-pointed
   - rather, a new one to be create

2. Pure functions

   - pure functions always produce the same output given some input
   - pure functions have no side effects and do not depend on or modify external state

3. First-class functions

   - functions are passed around and manipulated just like other objects

4. Prefer recursion over loops

   - recursion is more declarative and avoids mutable state

5. Referential transparency
   - a function invocation is equivalent to its return value
