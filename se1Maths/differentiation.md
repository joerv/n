How quickly does something change / slope of graph

### Straight line slope
Change in y / change in x.

### Slope of a curve
The slope at any one point of the curve is the gradient of the tangent of the
curve at that point.

### Calculate that from y = f(x)
y = x<sup>2</sup>


## Rules for differentiation
### chain rule
differentiate: (x<sup>2</sup> - 3x + 8)<sup>5</sup>

u = x<sup>2</sup> - 3x + 8

y = u<sup>5</sup>

dy/du = 5u<sup>4</sup>

du/dx = 2x - 3

dy/dx = dy/du . du/dx

= 5(2x-3)(x<sup>2</sup> - 3x + 8)<sup>4</sup>


differentiate: y = cos<sup>2</sup>x

u = cosx

du/dx = -sinx

dy/du = 2u

-2cos(x)sin(x)

### product and quotient rules
#### product
f(x) = g(x)h(x)

f'(x) = g(x)h'(x) + g'(x)h(x)


#### quotient
(u/v)' = vu' - uv'  /  v<sup>2</sup>

### Example
y = x<sup>9</sup>cos(x<sup>2</sup>)

u = x<sup>9</sup>

v = cos(x<sup>2</sup)

y' = (uv)' = u'v + uv'

= 9x<sup>8</sup>cos(x<sup>2</sup>) - x<sup>9</sup>.2xsin(x<sup>2</sup>)

= 9x<sup>8</sup>cos(x<sup>2</sup>) - 2x<sup>10</sup>sin(x<sup>2</sup>)


### implicit differentiation
#### Example
Find dy/dx for:

y<sup>3</sup> + 2xy -5x<sup>2</sup> = 0

Too difficult to solve for y.

Differentiate every term with respect to x

d/dx ( y<sup>3</sup> + 2xy -5x<sup>2</sup> ) = 0

3y<sup>2</sup>(dy/dx) + 2y + 2x(dy/dx) -10x = 0

(dy/dx)(3y<sup>2</sup> + 2x) = 10x - 2y

dy/dx = 10x - 2y   /   3y<sup>2</sup> + 2x

#### Example 4.6.2
x<sup>2</sup> - siny + xy = 0 Find dy/dx

2x - cosy(dy/dx) + y + x(dy/dx) = 0

(dy/dx)(x-cosy) = -y - 2x

dy/dx =  -y -2x  /  x-cosy

#### Example 4.6.3
Use implicit differentiation to show that 

(d/dx)(sin<sup>-1</sup>x) = 1 / sqrt(1-x<sup>2</sup>)

**Solution**

y = sin<sup>-1</sup>x     y is the angle whose sin is x

x = sin(y)

x - sin(y) = 0

Now differentiate

1 - cos(y)(dy/dx) = 0

dy/dx = 1 / cos(y)

cos<sup>2</sup>y + sin<sup>2</sup>y = 1

cosy = sqrt(1-sin<sup>2</sup>y) = sqrt(1-x<sup>2</sup>)  <-- correct


#### Example ...
Find slope of the tangent to the circle x<sup>2</sup> + y<sup>2</sup> = 1 at
point P(1/sqrt(2), 1/sqrt(2))

y = sqrt(1-x<sup>2</sup>)

dy/dx = -2x(0.5)  /  (1 - x<sup>2</sup>)<sup>2</sup>

= -x  /  (1 - x<sup>2</sup>)<sup>2</sup>

At point P: dy/dx = -1

**With implicit differentiation**

x<sup>2</sup> + y<sup>2</sup> - 1 = 0

2x + 2y(dy/dx) = 0

dy/dx = -x/y

= -1

### Parametric differentiation
x<sup>2</sup> + y<sup>2</sup> = 1

Can also be written in parametrics (works because of cos<sup>2</sup>y + sin<sup>2</sup>y = 1)

x = cos(t)  
y = sin(t)






