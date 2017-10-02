## example 1

bA|0|1
---|---|---
0|1|0
1|1|0

x = A`.B` + A`.B

= A`
## example 2

bA|0|1
---|---|---
0|0|1
1|1|1

X = A.B` + A`.B + A.B

= A.B` + B.(A`+A)

= A.B` + B

= A+B

## Example 3

cBA|00|01|11|10
---|---|---|---|---
0|0|0|0|0
1|1|1|1|1

X = A`.B`.C + A.B`.C + A.B.C + A`.B.C

= B`.C.(A`+A) + B.C.(A+A`)

= C

## Example 4
Use a karnaugh map to minimise the following expression:

X = A.B`.C + A`.B.C + A`.B`.C + A`.B`.C` + A.B`.C`

cBA|00|01|11|10
---|---|---|---|---
0|1|1|0|0
1|1|1|0|1

X = B` + A`.C


## Example 5
Use a KM to minimise the following logic expression:

X = B`.C`.D` + A`.B.C`.D` + A.B.C`.D`
+ A`.B`.C.D + A.B`.C.D + A`B`.C.D`
+A`.B.C.D` + A.B.C.D` + A.B`.C.D`

*B`.C`.D`* This section causes a problem because it only has 3 terms. Therefore
we can't put it into a single cell on our KM. Instead we replace it with this:

A.B`.C`.D` + A`.B`.C`.D`

abCD|00|01|11|10
---|---|---|---|---
00|1|0|1|1
01|1|0|0|1
11|1|0|0|1
10|1|0|1|1

One group of 8 and one group of 4

X = D` + B`.C
