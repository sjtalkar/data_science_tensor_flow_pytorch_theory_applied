# Data Science Reading Insights
[Hands On Machine Learning Code on Github](https://github.com/ageron/handson-ml3/blob/main/math_linear_algebra.ipynb)

Why Scale features
While the cost function has the shape of a bowl, it can be an elongated bowl if the features have very different scales. Figure 4-7 shows gradient descent on a training set where features 1 and 2 have the same scale (on the left), and on a training set where feature 1 has much smaller values than feature 2 (on the right)

When using stochastic gradient descent, the training instances must be independent and identically distributed (IID) to ensure that the parameters get pulled toward the global optimum, on average. A simple way to ensure this is to shuffle the instances during training (e.g., pick each instance randomly, or shuffle the training set at the beginning of each epoch). If you do not shuffle the instances—for example, if the instances are sorted by label—then SGD will start by optimizing for one label, then the next, and so on, and it will not settle close to the global minimum.

`If your model is underfitting the training data, adding more training examples will not help. You need to use a better model or come up with better features.`

`One way to improve an overfitting model is to feed it more training data until the validation error reaches the training error.`


Categorical features independence : Chi2 test . Multiple features and categorical against continuous ANOVA

Log Loss for classifications
https://towardsdatascience.com/understanding-binary-cross-entropy-log-loss-a-visual-explanation-a3ac6025181a

`Entropy is a measure of the uncertainty associated with a given distribution q(y).`
