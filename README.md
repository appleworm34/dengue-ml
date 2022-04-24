# Dengue: Predicting Disease Spread

## About

This is a mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence)

Our project focuses on predicting the total cases of dengue given the environmental and climate data of a given area.

![image](https://img001.prntscr.com/file/img001/kYbEdGG9Qb-4mVgJcnj2VA.jpeg)

Order of codes:
1. [Data Exploration and Visualisation](https://github.com/appleworm34/dengue-ml/blob/main/Data%20Exploration%20and%20Visualisation.ipynb)
   - (Explores the dataset using graphs and plots to better understand the relationships and visualise the data we are dealing with)
2. [Data Cleaning](https://github.com/appleworm34/dengue-ml/blob/main/Data%20Cleaning.ipynb)
   - (Filling in null values and focusing on important variables)
3. [Linear Regression](https://github.com/appleworm34/dengue-ml/blob/main/Linear%20Regression.ipynb)
   - (Using multi-variate Linear Regression to predict)
4. [K-Nearest Neighbours](https://github.com/appleworm34/dengue-ml/blob/main/K-Nearest%20Neighbours.ipynb)
   - (Exploring K-Nearest Neighbours and modifications to improve the model used for prediction)
5. [Support Vector Machine](https://github.com/appleworm34/dengue-ml/blob/main/Support%20Vector%20Machine.ipynb)
   - (Using Support Vector Machine to predict)

## Background
- Dengue fever is a disease caused by the dengue virus which is transmitted to humans via the bite of an infective Aedes mosquito.
- Dengue causes a wide spectrum of disease and in some cases, lead to hospitalisation or death. 
- Each year, an estimated 390 million dengue infections occur around the world, resulting in up to 36,000 deaths.


## Data source

- [DrivenData - DengAI: Predicting Disease Spread](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/page/82/)


## Problem Definition

- Can we predict the total number of Dengue cases based on the environmental and climate data?
- Which model among the ones we selected would be the best to predict it?

## Models Used

- Linear Regression
- K-Nearest Neighbours
- Support Vector Machine

## Conclusion

- We are able to predict the total cases to a certain extent (MAE of 15.986)
- Among the models we explored (Linear Regression, K-Nearest Neighbours and Support Vector Machine), SVM was the best to predict the total cases

## Data - Driven Insights
- We can further explore other models apart from the ones mentioned to find the best model to predict
- Variables did not have such an obvious relationship as we expected
- Possible to find more data that could help improve the accuracy of prediction

## What we learnt from this project:

- Collaborating using Google Colaboratory
- Different methods of filling in NULL values (interpolation)
- Complete flow of analysing and trying to solve a machine learning problem
- K-Nearest Neighbours for regression
- Support Vector Machine for regression
- Feature scaling
- K-Fold Cross Validation
- Bagging

## Contributors

- Da Jie(K-Nearest Neighbours,data exploration)
- Zack(Linear Regression,data cleaning)
- Xavier(Support Vector Machine,data visualisation)

## References

- <https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/page/80/>
- <https://www.analyticsvidhya.com/blog/2020/03/support-vector-regression-tutorial-for-machine-learning/>
- <https://realpython.com/knn-python/#reader-comments>
- <https://slidesgo.com/theme/world-mosquito-day#search-mosquito&position-1&results-1>
- <https://www.analyticsvidhya.com/blog/2021/06/power-of-interpolation-in-python-to-fill-missing-values/>
- <https://www.analyticsvidhya.com/blog/2018/03/introduction-k-neighbours-algorithm-clustering/>
- <https://stats.stackexchange.com/questions/82044/how-does-support-vector-regression-work-intuitively>
- <https://scikit-learn.org/stable/modules/cross_validation.html>
