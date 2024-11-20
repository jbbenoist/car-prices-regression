# car-prices-regression

This repository contains my submission project of module 11-1 from Professional Certificate in Machine Learning &amp; Artificial Intelligence by Berkeley ExecEd/Berkeley Haas

## The context

During the exercise, I have worked on analyzing data from a dataset from Kaggle that contains 426000 rows. The objective was to find what drives the price of a car.

## The results

After using some techniques to populate some missing data, do some cleanup in the dataframe and run multiple regression using the dataframe,
I have been able to find out that the Year is a very important component of the car price but there are also other components that can be impactful as pair,
for example: the odometers and the luxury brands.

The most successful regressions I have used to predict the car prices were Lasso and Ridge where both regressions had an R2 on the train set of respectively
0.793 and 0.796 and both got approximately 0.791 against the test set.

If you want more details on how I found these results or see the size of the samples used, you can find all the details in my notebook referred in the section below.

## The notebook

If you want to read the study, the notebook is accessible [here](https://github.com/jbbenoist/car-prices-regression/blob/main/assignment%2011-1.ipynb).
