* Discrete Random Variables
    Random Variable: An assignment of a value (number) to every possible outcome.

    Mathematically, we can think of it as function which maps every sample space to some value. They can be both discrete of continuous.

    Given that we have a sample space which maps to some outcome via the function H, what is the probability of getting a particular value x? This is the pX(x), which is P(X=x) (the probability of all outcomes for which the sample space gives us the value x after transformed by H).

    If we see the probabilities as frequencies of different outcomes, then the expected value is the frequency of each outcome multiplied by it's value.

* Properties of Expectations
    Let X be a T, Y and let Y = g(X): E[Y] = Sigma (y) gPY(y) or E[Y] = Sigma (x) g(x)pX(x) however be aware that it is rarely the case that E[g(X)] != g(E[X]) (it is if G is linear)

    Variance: a measurement of how var spread out the samples are, because it measures the average square of deviation, larger deviations are represented more heavily. var(X) = E[x^2] - (E[X])^2

* From Book
    A random variable is the real-valued function of the experimental outcome. Functions over random variables create another random variable.

    The random variable's associated probability mass function is the probability of each numerical value that the random variable can take. And a function of a discrete random variable defines another discrete random variable whose PMF is obtained from the PMF of the original random variable.

    To calculate the PMF of a random variable X, we take each possible values of the function, x, and collect all possible outcomes that gives rise to the event { X = x }, then add their probabilities to obtain pX(x).

    * Bernoulli Random Variable is a random variable that takes the values of 1 and 0 with the probability of p and 1-p. In practice it is very useful for modeling boolean states.

    * Binomial Random Variable is the random variable that takes the parameters n and p, and finds the probability of k outcomes out of the total n tries. The random variable is of the form n choose k * p ^ k (1 - p) ^ (1 - p)

    * Geometric Random Variable, a random variable for modeling when K will occur for the first time, and is called that because it decreases at a geometric rate. px*(k) = (1 - p)^(k-1) * p

    * Poisson Random Variable, the random variable with the distribution px(k) = c ^ (-lambda) * (lambda ^ (k) / k!). It is often used as a approximation of the binomial distribution but without the need to calculate the large factorials.

    Functions of random variables must also be random variables, since each value of the original random variable is mapped to a new value.

    The nth moment of a PMF is the expected value of X^n.
