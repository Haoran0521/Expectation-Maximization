04/23/2021

This is a simple expectation maximization problem.

In this question, we basically need to use expectation maximization to solve a 1-D exponential distribution clustering problem.

The important thing here:
1) What is the maximization for the parameters of an exponential distribution.
2) There are two different ways of explaining an exponential distribution: the parameter x represents the number of trails until success;
the parameter x represents the number of failures before success.
3) If the parameter x represents the number of trails until success, then the expectation of x will be 1 / p, which p is the probability of success. (condition 1)
4) If the parameter x represents the number of failures, then the expectation of x will be (1 - p) / p instead. (condition 2)

Follow this idea, we can get a maximization of parameter p easily:
condition 1: p = 1 / E(x)
condition 2: p = 1 / (1 + E(x))










