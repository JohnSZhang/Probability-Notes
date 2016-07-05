* Conditional Probability
    P(A|B) = probability of A given that B already occurred.

    P(A|B) = P(A ∩ B) / P(B)

    Note, although we now know that a particular even has occurred, it is still a complete sample space. So all the probability laws and axioms still apply.

* Multiplication Rule
    P(A ∩ B ∩ C) = P(A) * P(B | A) * B(C | (A ∩ B))

* Total Probability Theorem
    Partition a sample space into A1, A2, A3. Have P(B | Ai) for all i, then P(B) = Sigma i of P(B | Ai)

* Bayes Rule
    In order to find P(Ai | B), we can see it as P(Ai ∩ B) / p(B), which by multiplication rule is P(Ai) * P(B | Ai), expand out the bottom with Total Probability Theorem and we have P(Ai) * P(B | Ai) / Sigma j P (Aj) * P(B | Aj).

    This helps us find P(Ai | B) when all we are given are the P(A)s and the P(B | As), reversing the cause and effect relationship

    This is useful for learning from experimental data (partial observations) backwards to the cause in a systematic way.

* From Book
    Conditional probability provides ways to reason about outcomes via partial information (super useful).

    For Bayes Rule, P(Ai | B) is the posterior probability of the event Ai, because it comes from the observed event P(B), to separate it from the prior probability P(Ai)
