# This is my note of machine learning 

This course link is [here](https://www.coursera.org/learn/machine-learning/home/week), the famous one by Andrew NG.

## My goal of this course

learning different kind of algorithms and how to apply them. no need to create new one.


## what is machine learning

A computer program is said to  learn from experience E with respect to some task T and some performance measure P.

## Two major type of learning algorithms

1. Supervised learning
2. Unsupervised learning


Supervised algorithm is we teach computer to learn,giving the computer a lot of "right answer" data with labels

Unsupervised is the computer teach itself.

## Supervised learning

The supervised learning could be categoried by "regression" and "classification" problem.

Regression Problem cares continues value,like a quadratic line.

Classfication prolbem cares about discrete value,like (0,1)


## Unsupervised learning

given a ton of unlabeld data and let the machine to cluster them.

like Cocktail party problem, market segment.

The tool is [Octave online](https://octave-online.net/)

PPT 1 is [here](https://d3c33hcgiwev3.cloudfront.net/_974fa7509d583eabb592839f9716fe25_Lecture1.pdf?Expires=1654992000&Signature=MtZjP2el3YKyvuHTcSdgdfU1pyD-KN-1Jcn8g-AXNMdSxQCYAbRuDeTrUO84n0LstKzq~uKMaC176elgwn4wupPCM4pdXX7lWS~PVtyGofwKPINyD431J90ld9k80fnkZdgSW2dUK6Rj4PSZI2FKZXWBaq62690xiisb7MJzkWg_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

### Training set
m = numbers of training examples
x = input variable/features
y = output variable/"target " variable
(X^i,y^i),not exponentitation,but just  ith training example

[hθ(x) = θ0 + θ1x](https://www.holehouse.org/mlclass/04_Linear_Regression_with_multiple_variables.html). h is shortcut for hypothesis

The key problem is how to chose theta0 and theta1.

**cost function**: the accuracy of hypothesis functon.

The idea to choose theta0 and theta1 is h(x) fit our traning set y as close as possible,like min(hθ,y).

So we choose the **Square Error** function which is useful for most regression program.



MSE = $\frac{1}{n} \Sigma_{i=1}^n({y}-\hat{y})^2$. Other [mathematical-notations](https://krish9a.medium.com/mathematical-notations-for-machine-learning-markdown-5feb99e8d412)

### contour plot

like a bowl shape. to draw cost functions pictures of two parameters

it's hard to read and need to manual find the minimum point.

### gradient descent

common algorithm to find the minium of not only j but also other functions

with right simultaneous update: Fist calcus all, then assignment all. [link](https://www.coursera.org/learn/machine-learning/supplement/2GnUg/gradient-descent)

derivate is something like slop. it will move towards to zero. it can have positive and negative value.

gradient descent will reduce the step towards local mimnum. so,it is no nessary to change lining rate.

## Linear algebra

1. matrix: 2d or two dimension array.
2. vector: N * 1 matrix.
3. matrix addition: only happen when two the same matrix 
4. scalar multiplication: just apply the scalar number multiply every entry of the matrix.

*matrix multiple vector*

M * N matrix and N * 1 vector, the final one is M * 1 vector.
each element in M * 1 vector = sum(row[ij]* M[i]) 
 
*matrix multiple matrix*
 
 M * N  by N * O.
 
 first pull out of N * 1 vector and apply above rules. then combine the result together.
 
*some property*

Matrix A * B != B * A(not commutative)
A * B * C= A * (B * C) (associate)
identity matix = n * n and diagonal is 1 other is 0

matrix inverse. A * A^1 = I. A is m * m matrix.
transpose. flip the rows and colums  of A. Bij = Aji.

 
 








