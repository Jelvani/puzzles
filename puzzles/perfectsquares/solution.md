# Solution: Perfect Squares

No. Consider the integer x, we want to know if x(x+1) is a perfect square for some x. We can solve this through a lower and upper bound on the value of x(x+1):

x^2 < x(x+1) < (x+1)^2

The first perfect square less than x(x+1) is x^2. It is obvious the next perfect square follows as (x+1)^2. Since x(x+1) is between these 2 values, it is impossivle to do this through integers.