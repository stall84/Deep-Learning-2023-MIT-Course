## Example Problem

- We are going to input 2 features, _Hours Spent Studying_ and _Number Of Lectures_ to be able to predict $ \hat{y} $ will the person pass a class. <img src="./images/example-prob.png"></img>

- _'Y-hat'_ refers to:
<ul style="margin-left: 1.5rem; margin-top: -0.5rem;">
<li> y typically represents the actual observed value or the target variable.</li>
<li> y-hat ($\hat{y}$) represents the model's prediction for that target variable, based on the input features.</li>
</ul >

## Quantifying Loss

- In the graphic below we're simulating what the 'first run' of inputs would yield in an **_untrained_** neural network with the inputs $ [4,5] $
- The loss of our network measures the cost incurred from **_incorrect predictions_**

![quantifying-loss.png](./images/quantifying-loss.png)

## Empirical Loss

- The empirical loss measures the total loss over our **\_entire datased**\_

![empirical-loss.png](./images/empirical-loss.png)

## Binary Cross Entropy Loss

- Cross entropy loss can be used with models that output a probability between 0 and 1
- You'd use this on classifiction problems where there's a _yes_ or _no_ / _true_ or _false_ prediction needed.
- So this can answer the question of _"Will this student pass the class based on these lecture attendance and hours spent on final project"_

![binary-cross-entropy-loss.png](./images/binary-cross-entropy-loss.png)

## Mean Squared Error Loss

- For the situatino where we want to predict a _'continuous variable'_ or a discreet value.
- In our example problem this would answer the question _"What whill my final numeric grade be?"_
- The nn's predictions will then be values like _78_ or _91_

![mean-squared-error-loss.png](./images/mean-squared-error-loss.png)
