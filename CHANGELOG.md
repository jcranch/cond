## 0.5.0

- Four monoid structures for a boolean algebra (`AnyB`, `AllB`, `XorB`, `EquivB`)
- Typeclass altered so that {or, and, nor, nand, any, all} are no longer members
- Add instances for `()` and `(a,b,c)`
- `minimal` pragma (and corresponding definition)
- The opposite Boolean algebra (exchanging `true` and `false`, `&&` and `||`, etc)
- A more general instance for `Endo`
- Tested with GHC 7.0 - 9.6


## 0.4.2

- Add `instance Boolean b => Boolean (a -> b)`
- Tested with GHC 7.0 - 9.6
