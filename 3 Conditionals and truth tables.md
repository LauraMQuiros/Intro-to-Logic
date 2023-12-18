Monday lecture
# 7.1, 7.2, 7.3: extending Boolean with conditionals
[[Material Conditional]]: sentence with a conditional  of the form [[Antecedent]] $\rightarrow$ [[Consequent]] 
$¬ P \vee Q$ is equivalent to $P \rightarrow Q$. It's true if both are true, if both are false, if the result is true.

In the same way that "because" is not truth-functional because it implies causality "if ... then ..." is not truth functional because it doesn't account for the truth of the sentence if the antecedent is false.

[[Necessary Condition]]: when in $P \rightarrow Q$ we know if $P$ is true then $Q$ is also true, but $Q$ may be true anyways with false $P$. For example P: not doing the homework Q: failing
[[Sufficient Condition]]: when in $P \rightarrow Q$ we know that P is true guarantees Q is true like P: doing the homework Q: passing

When we negate the conditional we can translate the sentence to "unless". So $¬ (A \rightarrow B)$ means if not A then  not B, or unless A is not, then B.
$Q$ is a logical consequence of a series of premises $P_1, ..., P_n$ iff $(P_1, ..., P_n) \rightarrow Q$ is a logical truth.

[[Biconditional]]: $A \leftrightarrow B$ is equivalent to if and only if and just in case. Not to confuse with logical equivalence $\Leftrightarrow$ 

Conditionals and biconditionals in conversation:
[[Truth Conditions]]: Even though they have nothing to do with the truth of the claim they are assumed true, in order for the claim to have been made. E.g. the subject can see, the subject knows english. These are also called [[Conversational implicatures]] or just [[Implicatures]] 

[[Conversational implicatures]] or [[Implicatures]] can become false due to further elaboration. 

# 8.1, 8.2: Logic of 
[[Modus ponens]]: From P → Q and P, infer Q.
[[Contraposition]]: P → Q ⇔ ¬Q → ¬P
[[Biconditional Elimination]]: From P and either P ↔ Q or Q ↔ P, infer Q. 
1. The method of conditional proof: To prove P → Q, assume P and prove Q.
2. To prove a number of biconditionals, try to arrange them into a cycle of conditionals.
# 4.1, 4.2, 4.3: Truth Tables, Tautologies, logical truth
[[Logical Consequence]]: the conclusion must be true if the premises are true
[[Logical Necessity]]: truth of a sentence from an empty set of premises. This sentence is a [[Logical Truth]]
[[Tautology]]: any sentence whose truth table has only T’s in the column under its main connective.
[[TW-possible]]: sentence is true in some world that can be built using [[Tarski's World]]. Some sentences are [[Logically Possible]] like `sphere(b)` but not [[TW-possible]]. Vice-versa is not like that.
[[TW-necessary]]: a sentence is true in every world in which it has a truth value
[[Law of the excluded middle]]: P or not P and any variation of it. Always a tautology
[[TT-possible]]: a sentence is true in at least one row of its truth table
![[Screenshot 2023-11-30 at 21.01.14.png | 300]]

[[Logical Equivalence]]: if one is true, the other is as well and also with false ($a=b \wedge cube(a)$ and $a=b \wedge cube(b)$). However, they may differ in the value under the main connective in specific circumstances (`cube(a)` is T, `cube(b)`is F)
[[Tautological Equivalence]]: identical sequence of T and F under main connective with same reference columns in a truth table
[[Tautological Consequence]]: in a joint truth table, each row in which all premises are true, also consequence is true. All of them are also [[Logical Consequence]], but not vice-versa.

- - -
Wednesday lecture
# 3.6 Logical Equivalences
(Double negation and DeMorgan’s Laws) For any sentences P and Q: 1. Double negation: ¬¬P ⇔ P  
2. DeMorgan: ¬(P ∧ Q) ⇔ (¬P ∨ ¬Q)  
3. DeMorgan: ¬(P ∨ Q) ⇔ (¬P ∧ ¬Q)

# 4.5, 4.6 Normal forms

[[Negation Normal Form]]: if all instances of ¬ are followed by an atomic sentence. Can be done with repeated application of [[DeMorgan]] and [[Double negation]] and simplified with associativity $P \wedge (Q \wedge R)  \Leftrightarrow P \wedge Q \wedge R$, commutativity($P \wedge Q \Leftrightarrow Q \wedge P$) and idempotence ($P \wedge P \Leftrightarrow P$)



(The distributive laws) For any sentences P, Q, and R:  
1. Distribution of ∧ over ∨: P∧(Q∨R) ⇔ (P∧Q)∨(P∧R) 
2. Distribution of ∨ over ∧: P∨(Q∧R) ⇔ (P∨Q)∧(P∨R)

[[Disjunctive Normal Form (DNF)]]: sentences that are a disjunction of (one or more) conjunctions of (one or more) literals
[[Conjunctive Normal Form (CNF)]]: sentence that is a conjunction of one or more sentences, each of which is a disjunction of one or more literals

# 7.4: Truth-functional Completeness

Should we add more binary connectives? Maybe to supply for non [[Truth-functional connectives]]. We can map neither P nor Q to $¬(P \vee Q)$
A set of connectives is [[Truth-functionally complete]] if the connectives in the set allow us to express any truth function. 


- - -
Tutorial: idempotence, associativity, commutativity, distribution ,deMorgan, double negation
tt possible , tw possible, tautology
normal forms