Linear regression modeling for General Assembly Data Science Course

Dataset is here: https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/datasets/health_data.csv

Part 1: Use the first three columns to predict the number of doctors visits with a linear regression model. 

SOLUTION: http://nbviewer.ipython.org/gist/tarasuan/92689fe9934614b414f7


Part 2: Build a linear model that only takes age and education years as the input; then a linear model that takes just the age and the income. Which model fits the data better? Graph data with both of those regression lines using pylab or matplotlib to visualize the results.

SOLUTIONS
Age, Edu: http://nbviewer.ipython.org/gist/tarasuan/2a5688e326e310378dd9
Age, Income: http://nbviewer.ipython.org/gist/tarasuan/1297f38096b991920ffb


Part 3: Check that the two linear models from Part 2 and the linear model from Part 1 predict different values for the number of visits given some test data. 

ANSWER: The two models from Part 2 do yield different values. However not markedly so. 

Is the variation in the predictions consistent with your intuition?
Somewhat. Age would seem to be the most significant predictor, although the younger the person is, the more they go to the doctor as income rises.