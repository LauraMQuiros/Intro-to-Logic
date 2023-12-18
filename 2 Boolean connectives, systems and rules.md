# Chapter 3
3.1, 3.2, 3.3, 3.4, 3.5, 3.7
[[Boolean operators/connectives]]: `and`, `or` and `not`. Aka [[Truth-functional connectives]] because the truth value of a complex sentence built up using these connectives depends on nothing more than the truth values of the simpler sentences from which it is built.
[[Truth Table]]: we evaluate the truth value of a complex sentence by taking into account the values of the connectives and [[Atomic sentences]]. Limitations: 1. scales exponentially 2. can only rely on one truth-functional connective.
[[Literal]]: either [[Atomic sentences]] or the negation of one
[[Inequality]]: `¬(a=b)` is the same as `a != b` and they are both apt to use

[[Conjunction]]: sometimes not intuitive `large blue a = large(a) AND blue(a)`or `however`, `yet`, `nonetheless` and sometimes not reflect temporal difference `max left and ana was alone`. 
[[Disjunctive]]: always inclusive (at least one and possibly both true)
[[Neither/nor]]: `¬(Home(john) OR Home(mary))`. 
[[Scope]]: the scope of the boolean is set with parenthesis

[[DeMorgan]]: `¬(P OR Q) <-> (¬P AND ¬Q)` and also `¬(P AND Q) <-> (¬P OR ¬Q)`. 
[[Double negation]]: `¬¬P <-> P`

[[Truth Conditions]]: combinations of truth values for certain [[Atomic sentences]] that allow one or more complex sentences to be true. A good translation has in the original and translated same truth values in same circumstances and truth conditions.

# Chapter 5
[[Valid Inference Steps]]: the process of arising valid patterns of inference from boolean connectives
[[Conjunction Elimination]] or [[Simplification]]: asserting one of the two [[Atomic sentences]] conjuncted as true in its separate step
[[Conjunction Introduction]]: adding a conjunction step when we know both atomic sentences to be true
[[Disjunction Introduction]]: adding a disjunction once we know one of the atomic sentences to be true
[[Proof by cases]] or [[Disjunction Elimination]]: We begin with a desired goal that we want to prove, say S, and a disjunction we already know, say P ∨ Q. We then show two things: that S follows if we assume that P is the case, and that S follows if we assume that Q is the case. Since we know that one of these must hold, we then conclude that S must be the case.
[[Proof by Contradiction]], [[Indirect Proof]] or [[Reductio ad absurdum]]: To prove `¬S` we temporarily assume `S` and show that a contradiction follows from this assumption.
[[Contradiction]]: any claim that cannot possibly be true, or any set of claims which cannot all be true simultaneously (⊥). When one establishes a contradiction, any sentence can be asserted at all, however event though it would be valid, it wouldn't be a sound sentence.
[[TT-contradictory]]: two sentences are TT-contradictory if they cannot both be true in any circumstances

# Chapter 6

[[Subproofs]]: We say a subproof has been _discharged_ or _ended_ if the assumptions in which it was based do no longer hold. From the outside of the subproof, we can only cite the subproof as a whole, but in the subproof we can make use of premises from the outside.

[[Assess Validity]]: 
1. Understand what the sentences are saying.
2. Decide whether you think the conclusion follows from the premises.
3. If you think it does not follow, or are not sure, try to find a counterexample.
4. If you think it does follow, try to give an informal proof.
5. If a formal proof is called for, use the informal proof to guide you in finding one.
6. In giving consequence proofs, both formal and informal, don’t forget the tactic of working backwards.
7. In working backwards, though, always check that your intermediate goals are consequences of the available information.

[[Logical Truth]]: Result of all proofs without premises

- - -
