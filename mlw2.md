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

