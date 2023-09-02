# Cancer-Prediction-Model

The dataset and the content described below has been taken from YBI-Foundation.com for the better understanding of the readers. Please click the link below to download the dataset.

https://github.com/YBI-Foundation/Dataset/blob/main/Cancer.csv

# Content

   Dataset Information:

           Target Variable (y):

           Diagnosis (M = malignant, B = benign)
           Ten features (X) are computed for each cell nucleus:

                1. radius (mean of distances from center to points on the perimeter)
                2. texture (standard deviation of gray-scale values)
                3. perimeter
                4. area
                5. smoothness (local variation in radius lengths)
                6. compactness (perimeter^2 / area - 1.0)
                7. concavity (severity of concave portions of the contour)
                8. concave points (number of concave portions of the contour)
                9. symmetry
                10. fractal dimension (coastline approximation - 1)
                11. For each characteristic three measures are given:

                                                                      a. Mean

                                                                      b. Standard error

                                                                      c. Largest/ Worst

# Introduction to Logistic Regression
Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. The nature of target or dependent variable is dichotomous, which means there would be only two possible classes.

In simple words, the dependent variable is binary in nature having data coded as either 1 (stands for success/yes) or 0 (stands for failure/no).

Mathematically, a logistic regression model predicts P(Y=1) as a function of X. It is one of the simplest ML algorithms that can be used for various classification problems such as spam detection, Diabetes prediction, cancer detection etc.

# Types of Logistic Regression
Generally, logistic regression means binary logistic regression having binary target variables, but there can be two more categories of target variables that can be predicted by it. Based on those number of categories, Logistic regression can be divided into following types −

## 1. Binary or Binomial

In such a kind of classification, a dependent variable will have only two possible types either 1 and 0. For example, these variables may represent success or failure, yes or no, win or loss etc.

## 2. Multinomial

In such a kind of classification, dependent variable can have 3 or more possible unordered types or the types having no quantitative significance. For example, these variables may represent “Type A” or “Type B” or “Type C”.

## 3. Ordinal
   
In such a kind of classification, dependent variable can have 3 or more possible ordered types or the types having a quantitative significance. For example, these variables may represent “poor” or “good”, “very good”, “Excellent” and each category can have the scores like 0,1,2,3.

Logistic Regression Assumptions
Before diving into the implementation of logistic regression, we must be aware of the following assumptions about the same −

In case of binary logistic regression, the target variables must be binary always and the desired outcome is represented by the factor level 1.

There should not be any multi-collinearity in the model, which means the independent variables must be independent of each other.

We must include meaningful variables in our model.

We should choose a large sample size for logistic regression.                                                                      
