## Hyperbolic sine
**sinh(x) = e<sup>x</sup> - e<sup>-x</sup> / 2**

sinh(0) = 0

limit sinh(x) = limit<sub>x->inf</sub> e<sup>x</sup> - e<sup>-x</sup> / 2  = inf
- 0 / 2 = inf


## Hyperbolic cosine
cosh(x) = e<sup>x</sup> + e<sup>-x</sup> / 2

cosh(0) = 1+1 / 2 = 1

limit<sub>x->inf</sub> cosh(x) = inf + 0 /2 = inf

limit<sub>x->-inf</sub> cosh(x) = inf

## Hyperbolic tangent
tan(h) = sinhx / coshx = e<sup>x</sup> - e<sup>-x</sup> / e<sup>x</sup> +
e<sup>-x</sup>

## Example 2.4.2
Express 5e<sup>4x</sup> - 7e<sup>-4x</sup> in terms of sinh4x, cosh4x.

sinh(4x) = (e<sup>4x</sup> / 2) - (e<sup>-4x</sup> / 2)

cosh(4x) = (e<sup>4x</sup> / 2) + (e<sup>-4x</sup> / 2)

sinh(4x) + cosh(4x) = e<sup>4x</sup>

-sinh(4x) + cosh(4x) = e<sup>-4x</sup>

= 5(sinh(4x) + cosh(4x)) - 7(sinh(4x) - cosh(4x))

= 12sinh(4x) - 2cosh(4x)

## cos and sin recap
**cos<sup>2</sup>x + sin<sup>2</sup>x = 1**

## Example 2.4.3
Show that cosh<sup>2</sup>x - sinh<sup>2</sup>x = 1

need to prove that it lies on x<sup>2</sup> - y<sup>2</sup> = 1

cosh<sup>2</sup>x = (e<sup>x</sup>)<sup>2</sup> + 2e<sup>x</sup> .
e<sup>-x</sup> + (e<sup>-x</sup>)<sup>2</sup>  /  4

e<sup>x</sup> . e<sup>-x</sup> = 1


= cosh<sup>2</sup>x = e<sup>2x</sup> + 2 . 1 + (e<sup>-x</sup>)<sup>2</sup>  /  4

sinh<sup>2</sup> = e<sup>2x</sup> - 2 . 1 + e<sup>-2x</sup>  /  4

cosh<sup>2</sup> - sinh<sup>2</sup> = 1


