# Logistic regression

what is it and where to use for

classification usage:
Email:Spam or not
Transction: Fraudulent or Not
Tumor: malignant or Benign

something like yes or no , 0-1 and can be multiclass problem


## linear regression not suits for classficiation

The reason is classification is always discrete value,but the linear regression may expand the boundary.

Logistic function  htx = g(tTx) 
gt = 1/1+e-z
somethign like [that](https://www.coursera.org/learn/machine-learning-course/supplement/AqSH6/hypothesis-representation)

The *decision boundary* is the line that separates the area where y = 0 and where y = 1. It is created by our hypothesis function.


## cost function of logistic regression

$J(\Theta)$ = -$\frac{1}{m} \Sigma_{i=1}^my^ilog(\hat{y}^i) + (1-y^i)log(1-\hat{y}^i)$

if y=1 and y=0 has different functions

## advanced algorithm
 except graident descent,there are "Conjugate gradient", "BFGS", and "L-BFGS" which don't need to pick @,but more complex


## one2many
htx= P(Y=i;x;t) i=1,2,3
