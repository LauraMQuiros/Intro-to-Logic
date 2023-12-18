# Monday 
###  Syllabus 8: sets, ordered pairs, relations, functions 

[[Set]]: we will annotate sets as a group of elements in between curly brackets, separated by commas. They have no order
[[Membership]] of a set: $3 \in \{1,2,3\}$ and $4 \not \in \{1,2,3\}$ but elements are not always numbers, they can also be sets $\{1,2\} \in \{1, \{1,2\}\}$ 
[[Equality]] of sets: $A = B$, if A and B contain exactly the same members
[[Subset]]: $A \subseteq B$ , if every member of A is also a member of B.
[[Proper Subset]]: $A \subsetneq B$ if every member of A is also a member of B, but B contains at least one other member
[[Empty set]]:  $\emptyset$ set containing no element, subset of all sets
[[Intersection]]: $A \cap B$ is $\{x|x \in A$ and $x \in B\}$
[[Union]]: $A \cup B$ is $\{x|x \in A$ or $x \in B\}$. Inclusive or, it can also be in both sets
[[Difference]]: $A \setminus B$ is $\{x|x \in A$ and $x \not \in B\}$
[[Complement]]: $A^c$ is $\{x | x \not \in A\}$ aka $A^c = U \setminus A$ or set universal - set A

Sets can be groups of ordered pairs or ordered n-tuples. In these sets the order of the elements in the tuple or pair matter, and so do their repetitions. $<1,1,2> \neq <1,2> \neq <2,1>$. A [[binary relation]] is a set of ordered pairs. Some relations have properties, which we call functions. 
[[Function]]: $f= \{<x,y> | x \in \mathbb{N}, y \in \mathbb{N}, x^2=y\}$

LPL Ch. 1, sections 5 and 6: functions and sets
[[Function symbols]]: lowercase [[Predicate Symbols]] referring to the individual relationship with a subject resulting into another subject. As an example `father(max)` is not a property of `max` but rather a [[Complex Term]] referencing to max's father. When designing a language always ensure that all the [[Complex Term]]s refer to real instantiated objects. `sum(3,5)` 
[[Simple Term]]: is a [[Constant]]
[[Set theory]] as [[First-order Logic (FOL)]]: uses two predicates with [[Infix Notation]], identity `=` and set membership $\in$. Set membership is true if the constant to the left is a member of the set of the constant to the right. Right constant then has to be a set.
[[Arithmetic]] as [[First-order Logic (FOL)]]: similar with `+`, `=`, `x` and `<`. 
Alternative notation to [[Fitch Bar]]: we use symbol `.·.` to say therefore. 

- - -
# Wednesday

LPL Ch. 9
section 1-6: quantification; translation to FOL (no mixed quantifiers yet) 
[[Variable]]: behaves like a [[Constant]], but more of an auxiliary symbol that acts as a placeholder that indicates relationships between [[Quantifiers]] and the [[Argument]] positions of [[Predicate Symbols]].
Atomic [[Well-formed formula (WFF)]]s: A [[Complex Term]] that uses variables. Not a sentence, but can be used in combination w quantifiers to create sentences.
[[Well-formed formula (WFF)]]: any n-ary predicate followed by n [[Complex Term]], where terms can now contain either variables or individual constants.

The quantifiers can be used in combination with identity to express complex numerical claims.
[[Domain of Discourse]]: set of objects the sentences containing quantifiers are referring to. The sentences are only true or false relative to their domain.
[[Universal Quantifier]]: Makes universal claims $\forall x$, and its read "for all $x$ in the domain". In english we would say _everything, each thing, all things, and anything_.
[[Existential Quantifier]]: Makes existential claims $\exists x$ and it's read "for some $x$ in the domain". In english _something, at least one thing, a, and an_.

A [[Free variable]] $v$ is so until a quantifier $\exists v$ or $\forall v$ bounds it. Then it's a [[Bound variable]]. 
[[Sentence]]: is a [[Well-formed formula (WFF)]] with no free variables.

[[Satisfaction]]: we consider an object satisfies a [[Well-formed formula (WFF)]] if upon substituting any occurrence of free variable x with the object results in a true sentence. This sentence is also vacuously true if there are no objects x in the world.

The four Aristotelian forms are translated as follows: 
All P's are Q's : $\forall x (P(x) \rightarrow Q(x))$ this does not imply, tho [[Conversational implicatures]] may say it suggests so, that there are some $P(x)$
Some P's are Q's: $\exists x (P(x) \wedge Q(x))$ same but suggest that not all $P(x)$ are $Q(x)$
No P's are Q's:  $\forall x (P(x) \rightarrow ¬ Q(x))$
Some P's are not Q's: $\exists x (P(x) \wedge ¬Q(x))$

[[Universal Noun Phrases]]: english sentences starting with a language-equivalent of the universal quantifier. If used in combination with a [[Material Conditional]], parenthesis are necessary.
We call the equivalent with the existential quantifier "noun phrases with non-subject positions", because the evidence of the quantifier may not be at the beginning of the sentence.

LPL Ch. 12 section 1-3: proof methods for quantifiers 
LPL Ch. 13 section 1, 2: formal proof rules for quantifiers

[[Universal Elimination (Instantiation)]]: From $\forall x S(x)$, infer S(c), so long as c denotes an object in the domain of discourse.
[[Existential Introduction (Generalisation)]]: From S(c), infer $\exists x S(x)$, so long as c denotes an object in the domain of discourse.
[[Existential Elimination (Instantiation)]]: we give a name c to an x such that $\exists x S(x)$ 
[[Universal Introduction (Generalisation)]]: we introduce a random c and prove that S(c) then we can introduce $\forall x S(x)$

- - -
tutorial: 
what is and what is not a 
tautological consequence 
[[Logical Truth]]: get spurious rows out, all rest is T
[[Logically Possible]]: get spurious rows out, one is T