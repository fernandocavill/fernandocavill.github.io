# Multiple Features

except house pricing, there are other features like age,bedroom number.

n = number of features 
xⁱ = ith row vector
xᵧⁱ = specific value of Xⁱ

hypotheis become something like this:
hθ(x) = θ0x0+θ1x1+θ2x2+θnxn = θTx


## feature scaling and mean normalization

when we have multiple features like x1,x2,xn, the gradient descent will be like skewed eclipse and slow the movement.

So, there is a tricky if almost feature at the same range. the desceding will be increasing.

Xi = (Xi-ui)/si, ui is the average of xi and si is the max-min.

## how to choose alpha

if alpha is large, it may not be descent, but diverge
if alpha is too small, low convergence.
so choose the alpha correct, and the J theta descends and flatten

## polynomail Regression

when the hypothesis function is linear function which don't fit the data

1. choose different curve like quadratic,cube, square root
2. combine variables like x = x1.x2

*feature scaling is tremendous large*

## normal equation

Normal equation is alternative way to calcus minJ without gradient descent.

it don't need to alpha and iterate. 
it calcus the theta and used in 10,000 n variables.

