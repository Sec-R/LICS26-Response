Dear Reviewers,

Thanks to all for the comments and references! After a thorough check of the references provided by Reviewers B and C, we do believe there is some overlap between the results of Sections 3 and 5 and previous works. It is our mistake in the literature search; we did not realize that rational transduction and trace language were the right options to investigate.

We are especially grateful for Reviewer A's detailed comments and review, and Reviewer B and C's detailed pointers to all kinds of references. The only clarification we want to make is that the result of Section 4 is strictly stronger than any similar statements made in the "rational" way. This is because, by definition, rationality admits the star axiom where \(X^* = 1 + X + X^2 + \cdots\), whereas we not only achieve the same decidability result under a weaker premise, but also show that the equational theory of such Kleene algebra is the same as its \(*\)-continuous version.

Again, thanks for all of the effort and comments that have been made! Below are some responses to the minor points made by the reviewers.

# Review A:
> Can you clarify the definition of \(L_C\) (see detailed question below)?

Thanks for the detailed comments and appreciation for the work! Intuitively, \(L_C\) is the quotient language of \(L\) under the equivalence class \(C\). More precisely, it is stated as part of Theorem 2.3, but there it is written in the notation of \(L_E\) instead of \(L_C\). It is a bit confusing here. We will separate the definition from the theorem and make the notation clear in our next version.

# Review C:
> The authors also say in the conclusion that the construction in Result B is strongly inspired by [Kozen and Smith 1997].

Ah. By strongly inspired, we only mean that we need to find the normal forms \(e_1\) and \(e_2\) such that \(L_C(e_1) = L_C(e_2)\) iff \(L(e_1) = L(e_2)\). The rest of the details of our proof are completely different from Kozen's.
