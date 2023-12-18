[The Remote Environment: uwp.rug.nl](http://uwp.rug.nl/)
## Chapter 1
[[Propositional Logic]]: uses [[Argument]]s which validity depends on the meaning of [[Connectives]] such as `not`, `and`, `if.. then..` and others. Here [[Atomic sentences]] are single uppercase letters.
[[First-order Logic (FOL)]]: uses [[Argument]]s which validity depends on the [[Quantifiers]] `all`, `some`. Here [[Atomic sentences]] are decomposed into [[Predicate Symbols]] and [[Constant]]s.

[[Constant]]: constants are lowercase words or numbers referring to a single existing object (never null). 
[[Objects]]: may be referenced by no [[Constant]]s or several of them
[[Predicate Symbols]]: determines a relationship between [[Argument]]s or a property of a single [[Argument]]. Can be used with [[Infix Notation]], such as the identity predicate `=` in `a = b` or with [[Prefix Notation]] such as `Taller(a,b)`. 
[[Arity]]: number of arguments fixed to a certain [[Predicate Symbols]] 
[[Determinate Property]]: evaluates each predicate with a relation or function of the same [[Arity]].
[[Tarski's World]]: is limited to a fixed given set of [[Predicate Symbols]] with [[Arity]] up to 3.
[[Atomic sentences]] are formed by putting a predicate of arity n in front of n names (enclosed in parentheses and separated by commas). The order of the names is crucial in forming atomic sentences.

## Chapter 2
[[Argument]]s: is any series of statements in which one ([[Conclusion]]) is meant to follow from, or be supported by, the others ([[Premises]]).
[[Logical Consequence]]: property of a [[Conclusion]] of a [[Logically Valid]] argument, otherwise is not.
[[Logically Valid]]: iff the conclusion must be true on the assumption that the premises are true. This doesn't mean the premises have to be true. 
	An argument using identity is valid if the conclusion can be reached with =Intro and =Elim

[[Valid Argument]]: guarantees the truth of its conclusion on the assumption that the premises are true
[[Sound Argument]]: when the premises are true and we have a [[Valid Argument]]

[[Fitch Bar]]: separates [[Premises]] from [[Conclusion]], classifying that way all [[Argument]]s
[[Proof]]: step-by-step demonstration that a [[Conclusion]] (say S) follows from some [[Premises]] (say P, Q, R)
[[Formal Systems]]: a formalised method to solve a proof (inference scheme??)💥💥
[[Formal Proofs]]: employs a fixed stock of rules and a highly stylised method of presentation, as opposite to [[Informal Proofs]] which is more of a description.

[[Indiscernibility of Identicals]] or [[Substitution]]: observation by which we realise all objects that are equal to each other share the same properties
[[Identity Elimination]]: formal rule that allows to "eliminate" the use of a [[Constant]] in favour of an equal [[Constant]]. `=Elim` requires the **first** element of the identity and the identity to be within the arguments of the proof.
[[Identity Introduction]] aka [[Reflexivity of Identity]]: formal rule that allows to introduce identity statements `=Intro` may be necessary if `a=b` and we want to get to `b=a` we first need an equivalence in which to substitute `b`, like `a=a`. 

[[Symmetry]]: identity is symmetric, we can introduce `a=b` from `b=a`. 
[[Transitivity]]: identity is transitive bc from `a=b` and `b=c` we can introduce `a=c`.
[[Inverse]]: relation between two [[Predicate Symbols]] that refer to the same relation but in opposite directions, like `smaller` and `bigger`. 
[[Bidirectionality]]: some predicates like `Between(a,b,c)` are bidirectional which means `Between(b,a,c)` is just as valid.
[[Reiteration]]: we can just reiterate sth `Reit`. 

[[Deductive System]]s: system for presenting formal proofs. Not same as [[Formal Systems]] which are methods of solving those proofs. Example is $\mathcal{F}$ or [[Fitch-style system]], which derives from $\mathcal{F}$.
[[Fitch-style system]]: has a [[Fitch Bar]] and [[Justification]]s which are just the [[Formal Rule]] applied to which lines as arguments to result in the premise of that line