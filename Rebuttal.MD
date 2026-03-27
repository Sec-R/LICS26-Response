Dear Reviewers,

Thanks for all for the comments and reference! After a thorough checking through the reference provided by Reviewer B and C, we do believe there is some overlapping between the results of Section 3 and 5
have some overlapping with the previous works. It is our miss in doing literature search, we didn't realized the rational transduction and trace language should be the right ones to investigate.

We are especially grateful for Reviewer A's detailed comments and reviews, and Reviewer B and C's detailed pointing towards all kinds of reference. The only clarification we want to make is the result of Section 4 is strictly stronger than any similar statements made in the "rational" way. This is for the reason that by definition rational admits the star axiom where X*=1+X+X^2+..., whereas we not only achieve the same decidability result under a weaker premise, but also shows the equational theory of such Kleene Algebra is the same with its *-continuous version.

Though some of the repeated efforts have been made, but we are still excited about the reference Reviewers gave. In the literature of Ibarra (JACM 1978), we actually found a way to encode Turing machine halting problem
into the Rat({a,b}* \times {c}*), which was exactly the obstacle for us to get the undecidability result for general Kleene Algebra! After having a discussion, we do believe such a method is plausible, yet more details are 
to be worked out, but probably we may be able to see a proof in the really near future.

Again, thanks for all of the efforts and comments have been made! Below down are some responses to the minor points made by reviewers.

Review A:
- Can you clarify the definition of L_C (see detailed question below)?

Thanks for the detailed comments and appreciation for the work! Intuitively, L_C is the quotient language of L under the equivalence class C. Strictly, it is stated as part of the Theorem 2.3 but it was in the notation of L_E instead of L_C. It is a bit confusing here. We will separate the definition from the theorem and make the notation clear in our next version.


Review B:
- The question is how you see the overlap between your results and existing results.

The response is stated above. But really thanks for the reference to Ibarra (JACM 1978)! it is very important to us.

Review C:
- The authors also say in the conclusion that the construction in Result B is strongly inspired by [Kozen and Smith 1997].

Ah. By strongly inspried we only mean that we need to find the normal form e1 and e2 such that L_C(e_1)=L_C(e_2) iff L(e_1)=L(e_2). The rest of details of our proof is completely different from Kozen's.

- Not only language equivalence, but even universality is undecidable (i.e. given an expression p, does KA*+C \models (a+b+c)* = p).

Actually we plan to prove the universality KA+C \models (a+b+c)* = p is undecidable. Hopefully we will work out:)
