# PClub Machine Learning Task

This repository contains my implementation of PClub Loss function comparison task.

- In this task i have compared 4 loss functions.
1. | x - x_cap | ^ 3
2. | x - x_cap | 
3. | x - x_cap | ^ 4
4. | x - x_cap | ^ 7

Using two machine learning algorithms. **Linear regression** and **Polynomial regression**

<hr >

## Dataset

I created my own dataset using randomly generated values of x and two very simple funtions one is *linear* and one is *second degree polynomial*.
This was the easiest approach as suggested by som.

<hr >

## Model

I have implemented all the models from scratch and all files are available in the repository.

All are very basic models with some hyperparameter tuning (only two alpha and no of interation in all models).

<hr>

## Final Losses

1. **0.068**
2. **-0.131**
3. **37.933**
4. **1.064 * 10^8**

<hr>

## Comparison

- As we see in case of linear regression A loss function performed better than B.
- And in the case of polynomial regression there is a very large difference between final losses of Loss function C and D. Here Loss funtion C is wins by a very huge margin.

So finally, |x - x_cap| ^ 3 is better than |x - x_cap| in case of linear regression.

and |x - x_cap| ^ 4 is far better than |x - x_cap| ^ 7 in case of polynomial regression.

