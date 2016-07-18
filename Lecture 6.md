* Discrete Random Variables Cont.
    Conditional PMF is just normal PMF but with the extra condition given. PX|A(x) = P(X = x | A).

    Expected value of X given A: E[X|A] = Sigma X xPX|A(x). Like your normal expectation, but with conditional PMF.

* Geometric PMF
    It's a random variable over the set of all integers. It has the expected value of Sigma k = 1 -> infinity k * (1-p)^(k-1) * p

* Total Expectation Theorem
    Partition of sample space into disjoint evens A1, A2... An. Following the sample space partition theorem, E[X] = P(A1)E[X|A1] + ... + P(An)E[X|An]

* Join PMFs
    PX,Y(x, y) = P(X = x and Y = y). PX|Y(x | y) = P(X = x | Y = y) = PX,Y(x, y) / PY(y)

* From Book
   Mean and Variance of Some Common Random variables:
   * Bernoulli: expected = p, 2nd moment = p, variance = p(1-p)

   * Discrete Uniform Random Variable: expected = (a + b) / 2, 2nd moment = 1/6 * (n + 1)(2n + 1), variance = (n ^ 2 - 1) / 12. For general form var(X) = ((b - a + 1) ^ 2 - 1) / 12

   * Poisson: expected = lambda, variance = lambda

   * Functions from multiple random variables:
    The function Z = g(X, Y) has the PMF of pZ(z) = sigma (x, y) | g(x, y) pX.Y(x, y). Basically, the PMF function it she sum of all possible g values from their XY random variables.

    * Function with more than 2 Random Variables: It's very similar to the above 2 function version of random variables.

    The marginal PMFs of X and Y can be obtained from the joint PMFs with the formula pX(x) = sigma y pX,Y(x, y) and pY(y) = sigma x pX,Y(x, y)

    Conditional PMF is similar to the usual definition of conditional probability, IE. pX|A(x) = P(X=x|A) = P(X=x intersect A) / P(A)

    Conditional PMF of X given Y can be used to calculate the marginal PMF of X via the formula px(x) = sigma PY(y) * pX|Y(x|y)

    Similarly, the conditional expected values of x can be thought of as taking the expectation of an ordinary PMF over the new universe of the already occurred event.
