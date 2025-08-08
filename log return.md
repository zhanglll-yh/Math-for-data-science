# What does log return mean?

A log return measures the percentage change in price, but on a logarithmic scale.

log return for price from time t1 to t2 = ln(P_t2/P_t1)

Wile a normal percentage return of this := (P_t2-P_t1)/P_t1

Log return have some very good characteristics compare to the normal one:

1.Additivity(handle compounding natually) :

from t1 to t2 to t3

ln(P_t3/P_t1)=ln(P_t2/P_t1)+ln(P_t3/P_t2)
while in most cases this "addicitvity" can't apply to the normal one.

2. Symmetry:

Let's suppose the intitial price was 1,and it has changed to (1+x) during a period of time

If the x is very small,than we have ln(1+x)≈1+x

Then log return = ln((1+x)/1)=1+x

and since -(1+x)≈ln(1/(1+x)),minus that improved "log return", it get back to 1 (the initial price)
But not the same fot the normal one.

3. Shrinking extreme values a bit, which reduces skew




