For when you have lots of things that can happen in different orders, we can
avoid doing an explicit calculation by using a branch result for the number of
ways of arranging r objects out of n.

This gives the **BINOMIAL DISTRIBUTION**

We have a trial with possible results A,A'

I know P(A) = p and P(A') = 1-p = q

P(A) + P(A') = 1

if the trial is repeated n times then the probability of r occurrences of A and
n-r occurrences of A' is:

n!/r!(n-r)! . p<sup>r</sup>(1-p)<sup>n-r</sup>

Les use the probability of r successes from n trials is:

n!/r!(n-r)! . p<sup>r</sup>(1-p)<sup>n-r</sup>

Ex 6.3.3

A reactor produces a chemical, 87% of the batches are acceptable with 10 batches
are now selected.

(a) P(0 acceptable batches)

p = 0.87   q = 0.13        n=10  r=0

P(0 acceptable) =

10!/0!(10-0)!  . (0.13)<sup>10</sup>

 = 1.37x10<sup>-9</sup>
