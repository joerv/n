### Rule 10
A + A.B = A

Can prove this with a truth table:

A|B|A.B|A+A.B
---|---|---|---
0|0|0|0
0|1|0|0
1|0|0|1
1|1|0|1

first column equals last column.

### Rule 11
A+A`.B = A+B

A|B|A`.B|A+A`.B|A+B
---|---|---|---|---
0|0|0|0|0
0|1|1|1|1
1|0|0|1|1
1|1|0|1|1

Last 2 columns are equal

### Example
Use boolean algebra to simplify the expression:

A.B+A.(B+C)+B.(B+C)

A.B+A.B+A.C+B.B+B.C

A.B+A.C+B+B.C

A.B+A.C+B

A.C+B
