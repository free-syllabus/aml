## Linear Regression

### Required Study Materials

1. [Linear Regression and Models (by StatQuest)](https://www.youtube.com/watch?v=PaFPbb66DxQ&list=PLblh5JKOoLUIzaEkCLIUxQFjPIlapw8nU)
2. @todo: Find "Linear Regression by Andrew Ng" (playlist was removed from youtube)

1. show a typical [ML pipeline](https://broutonlab.com/ghost/content/images/blog/how-machine-learning-pipelines-work/how-ML-pipeline-Work.png), 
on this lesson we will focus on the Data Preparation part (usually the hard part of the pipeline) and as a simple model use Linear regression
2. predicting [flat price in Brno](https://www.sreality.cz/en/search/for-sale/apartments/brno) based on one feature:
    * teams of 3
    * make a dataset of at least 10 flats
    * think about what features influence the flat prices and which one is the most important
    * 15 min, check which feature they selected
    * think about the equation of linear regression and try to guess the parameters, then make the [model](https://www.graphpad.com/quickcalcs/linear1/)
    * 10 - 15 min, if they have spare time they can add more flats
    * let them evaluate the model on our test set, write the results on the board @todo make test set
3. predicting flat price based on more features:
    * think about other features that might influence the price, 10 min
    * describe to them categorical vs numerical features, sort their ideas into these two buckets (one hot enconding)
    * explain OHE and binning for categorical features encoding
    * try out these techniques - select multiple features they believe are important, use [multiple linear regression](https://stats.blue/Stats_Suite/multiple_linear_regression_calculator.html), try different variations of features
    * build a model they are happy with, discuss the best set of features; may be more than 40 mins
    * if somebody is quick, tell them about normalization, how does GD behave when the data is not normalized?
    * make a new evaluation on the test set with new models, are they better? (if not significantly better - discuss why)
    * [optional] fun task if enough time: choose one person that knows well a flat in Brno, send him to a different group and try to estimate the price of the flat

4. Predict demography of given countries (Italy, China, Egypt, Czech Republic)
  * Task is to predict ratio of population for given age range (-18 and 60+)
  * Use the publicly available data from webs
  * Predict for years 2050 and 2100
  * [teacher] Be aware that ratio is relative number and sum of them should be 100%
5. [optional] discuss deployment, monitoring
6. [optional] space to find a team for the project


@todo give them colorful papers: in progress, need help, done

### Reasoning
* try out feature extraction - which features are important
* get familiar with tricks for feature encoding - OHE, binning
* work with linear regression - get the intuition behind the equation, think about the coefficients and what they mean, try to compute the prediction for new data on their own
