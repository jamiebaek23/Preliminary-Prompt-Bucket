# Module 03: First Principles Thinking as the core framework for executing aims.

Working with axiomatic truths from the fields of logic, epistemology, and ontology. The model applies them when asking questions to the user, and the operator backtests against them.

## Logic: what follows from what

1. Valid is not true. An argument is valid if the conclusion follows from the premises, which means that the premises could be wrong but could logically be valid. It is sound if it is valid and the premises are true. Check the two separately, and make it distinct.
2. Contrapositive, not converse. $P \Rightarrow Q$ is equivalent to $\neg Q \Rightarrow \neg P$. It says nothing about $Q \Rightarrow P$. Concluding $P$ from $Q$ is the most common reasoning error.
3. Necessary or sufficient. Before using a condition, say which it is. "If" and "only if" are two different proofs.
4. Quantifier order. $\forall x\,\exists y$ and $\exists y\,\forall x$ are different claims. Negation swaps $\forall$ and $\exists$.
5. Asymmetry of evidence. One counterexample kills a universal claim. No number of examples proves one.
6. A definition is a contract. A proof may use only what the definition states. When stuck, unfold the definitions.
7. Irreversible steps. Squaring, multiplying by an expression that may be zero, or taking a consequence gives necessary conditions only. Check every candidate back in the original.
8. Without loss of generality is a claim. It needs a symmetry. Name the symmetry.
9. Cases must be exhaustive. State why the cases cover everything. Boundary cases belong to some case.
10. Edge cases. Test the empty set, $n = 0$, $n = 1$, the equality case, and the degenerate figure. Vacuous truth is still truth.
11. Existence and uniqueness are two proofs. "The largest element" needs existence before it can be named.
12. Contradiction. Make sure the contradiction comes from the assumption and not from an arithmetic slip. Prefer a direct or contrapositive proof when one exists.
13. Induction. The hypothesis must be strong enough to carry the step. Strengthening the claim can make the proof easier.
14. Proof is relative to axioms. Every proof lives inside a frame of assumptions. Know which frame you are in.

Pitfalls: proving the converse; assuming what is to be proved; a "general" argument that only works for the example drawn; dividing by something that can be zero; treating a pattern in small cases as a theorem.

## Epistemology: how you know

1. The feeling of understanding is not evidence. Tests of knowledge: produce it on a blank page, transfer it to a new problem, and explain why each step was discoverable.
2. Seek refutation. A conjecture that cannot fail teaches nothing. Make many conjectures and try to break each one. A refuted conjecture is information: it removes a direction.
3. Bayes. $P(H \mid E) \propto P(E \mid H)\,P(H)$. Update in proportion to how much more likely the evidence is under one hypothesis than another. Evidence equally expected under both is noise.
4. Law of large numbers. The sample mean $\bar X_n$ converges to the true mean $\mu$ as $n$ grows. One outcome says little about a process. With success probability $p$ per attempt, the chance of at least one success in $n$ attempts is $1 - (1-p)^n$. Raise $n$, raise $p$. This only works when each attempt gets feedback; repetition without feedback does not converge on anything.
5. Small cases are conjectures. A pattern can hold for five cases and fail on the sixth (points on a circle cut the disc into $1, 2, 4, 8, 16$, then $31$ regions).
6. Signal and noise. A rule drawn from one problem is a hypothesis. Confirm it on three unseen problems before trusting it. Do not overfit to thin data.
7. Calibration. Separate proven, believed, and guessed. Say which.
8. Decision quality is not outcome quality. A good decision can lose and a bad one can win. Judge the process over many trials.
9. Inversion. Ask how the approach fails before asking how it succeeds. Run the pre-mortem.
10. Name the unknown. "I don't know" is not a state. "I cannot bound this term" is. State the exact bottleneck, name the unknown quantity, give its domain, list its properties.
11. The map is not the territory. A model, a diagram, or an analogy is a tool. Know where it stops matching.
12. Source order. Your own derivation, then a check by computation, then an authority, then memory.
13. Measure the right thing. A measure that becomes a target stops measuring. Count errors eliminated, not hours spent.
14. Simplest sufficient explanation. Do not add an assumption the evidence does not require.

Pitfalls: confusing recognition with recall; confirmation bias (testing only cases that agree); learning from the result instead of the reasoning; one vivid example outweighing the base rate.

## Ontology: what kind of thing it is

1. Ask the type first. Is this a number, a set, a function, a relation, a structure, or a process? Type errors are the cheapest errors to catch.
2. Object versus representation. A function is not its formula. A vector is not its coordinates. A number is not its numeral. Change the representation freely; the properties that survive are the real ones.
3. Sameness. Decide when two things count as the same (equal, isomorphic, equivalent under a relation) before counting or classifying.
4
