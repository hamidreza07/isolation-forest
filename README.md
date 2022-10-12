# ISOLATION FOREST:
Isolation Forest is an algorithm originally developed for outlier detection that consists in splitting sub-samples of the data according to some attribute/feature/column at random. The idea is that, the rarer the observation, the more likely it is that a random uniform split on some feature would put outliers alone in one branch, and the fewer splits it will take to isolate an outlier observation like this. The concept is extended to splitting hyperplanes in the extended model (i.e. splitting by more than one column at a time), and to guided (not entirely random) splits in the SCiForest model that aim at isolating outliers faster and finding clustered outliers.

Note that this is a black-box model that will not produce explanations or importances - for a different take on explainable outlier detection see [OutlierTree](https://www.github.com/david-cortes/outliertree).

## Description
In this repositories we tried  to identify best model of isolation forest. In order to do that we check and study 3 main site (github , pypi and kaggle) for finding best isolation forest model. As you know isolation forest model is used for detecting outliers and the sklearn itself, has a one ensemble method for that. The table below is our best effort to review other methods in aspect of pros and cons :





| id | name of project           | advantages                                                                                                                                                                   | disadvantages                                                                | link                                                                               | sample file                                                                                             |
| -- | ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| 1  | iForest                   | simplicity-install without any configuration<br>self configuration of isolation forest                                                                                       | Missing data and categorical data not supported                              | https://github.com/donyafoz/iForest                                                |                                                                                                         |
| 2  | plot\_anomalies           | simplicity-visualiztion base on iForest                                                                                                                                      | Missing data and categorical data not supported                              | https://github.com/katjawittfoth/Isolation\_Forest                                 | [plot\_anomalies](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/plot_anomalies) |
| 3  | kaggle                    | simplicity-self configuration of isolation forest                                                                                                                            | Missing data and categorical data not supported                              | https://www.kaggle.com/code/rgaddati/unsupervised-fraud-detection-isolation-forest | [kaggle](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/kaggle)          |
| 4  | coniferest                | simplicity-self configuration of isolation forest<br>better performance than sklearn model                                                                                   | Missing data and categorical data not supported                              | https://github.com/snad-space/coniferest                                           | [coniferest](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/coniferest)      |
| 5  | isotree                   | simplicity-self configuration of isolation forest-support missing  and categorical data                                                                                      | \-                                                                           | https://github.com/david-cortes/isotree                                            |[isotree](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/isotree)         |
| 6  | DIFFI                     | simplicity-visualiztion base on iForest-No pip installation required-<br>messurment of outliers by f1score -detect ouliers by cause                                          | Missing data and categorical data not supported<br>only suppurt numpy arrays | https://github.com/mattiacarletti/DIFFI                                            |[DIFFI](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/DIFFI)           |
| 7  | h2o                       | self configuration of isolation forest-<br>support missing  and categorical data<br>determind different range of outliers by user<br>handle big data-detect ouliers by cause | \-                                                                           | https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/if.html#               |[h2o](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/h2o)             |
| 8  | pyod                      | simplicity-self configuration of isolation forest                                                                                                                            | Missing data and categorical data not supported                              | https://github.com/yzhao062/pyod                                                   | [pyod](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/pyod)           |
| 9  | BorutaShap                | simplicity-self configuration of isolation forest                                                                                                                            | Missing data and categorical data not supported                              | [https://github.com/Ekeany/Boruta-Shap](https://github.com/Ekeany/Boruta-Shap)     |[BorutaShap](https://github.com/hamidreza07/isolation-forest/tree/main/sample%20file/BorutaShap)      |
| 10 | sklearn.isolation\_forest | simplicity-sklearn configuration of isolation forest                                                                                                                         | Missing data and categorical data not supported                              | \-                                                                                 |                                                                                                         |
