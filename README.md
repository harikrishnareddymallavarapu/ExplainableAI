# ExplainableAI

#Interpretable Models

1.  Linear regression, logistic regression and the decision tree are commonly used interpretable models.
2.  Monotonicity is useful for the interpretation of a model because it makes it easier to understand a relationship
3.  Some models can automatically include interactions between features to predict the target outcome
4.  Interactions can improve predictive performance, but too many or too complex interactions can hurt interpretability

#Linear Regression

1. Interpretation of Numerical Feature - An increase of feature xk by one unit increases the prediction for y by βk units when all other feature values remain fixed
2. Interpretation of a Categorical Feature - Changing feature xk from the reference category to the other category increases the prediction for y by βk when all other features remain fixed.
3. The importance of a feature in a linear regression model can be measured by the absolute value of its t-statistic. The t-statistic is the estimated weight scaled with its standard error.The importance of a feature increases with increasing weight. The more variance the estimated weight has (= the less certain we are about the correct value), the less important the feature is.
4. Weight Plot : ![image](https://user-images.githubusercontent.com/24980224/117407396-1f17b000-af2c-11eb-9b93-7fc073ad7f76.png)

5. 
