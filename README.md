## The Ordinals in Cedille

This repository houses the code for a project I've done for CS5860: Lambda Calculus at the
University of Iowa. Included should be a .pdf documenting with the report.

Inside [typed-encoding](./typed-encoding/) should be a few different approaches to encoding the
ordinals in Cedille. The work is largely derived from Martin Escardo's great work here https://www.cs.bham.ac.uk/~mhe/papers/ordinals/ordinals.html.
Where I differ is that I'm able to much more easily type addition, multiplication, and exponentiation uniformly thanks to Cedille's impredicativity.

Inside [untyped-church-encoding](./untyped-church-encoding) is a brief effort I gave to encoding
ordinals as Church and Kleene originally defined them in their article *Formal definitions in the theory of ordinary numbers*, published in 1937.


## Further Work
Here are some things I had hoped to cover but had to restrict from the scope of the final
report. Some of these I tried and came to dead-ends, some I didn't get the time to do.

- Going beyond epsilon_0.
- Defining addition, multiplication, and exponentiation in the untyped lambda calculi.
- Proofs of associativity and distributivity over ordinal addition and multiplication (usind OrdEq).
- Casts between the inductive datatype representation and impredicative quantification representation found in [Ordinal-03](./typed-encoding/Ordinal-03.ced) and [Ordinal-02](./typed-encoding/Ordinal-02.ced), respectively.
