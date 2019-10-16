# Udacity Capstone Project

This repo contains my final project on Udacity Data Scientist nanodegree! \o/

I decided to use a dataset from Kaggle. this dataset was provided by Home Credit and the objective is predict if the applicant's will repayed or not their loan.

## Motivation

My motivation to work with this project is that I really want to apply artificial intelligence in financial systems, and I love Kaggle Community, it's a amazing experience be part of this.

## Strategy 

To work in this project I broke it into 5 steps.

![](https://github.com/DougTrajano/udacity_capstone_project/blob/master/images/presentation.png)

I find some algorithm that can works and some needs to improve the results.

You can see more in Medium's post [here](https://medium.com/@dougtrajano/ia-applied-in-credit-risk-home-credit-b70412ef8f02).

## Results and conclusions

Let’s see below the Kaggle Score for each algorithm that I tried here.

![](https://miro.medium.com/max/759/1*wtQiADcUh-Q3QgqJOy5gJA.png)

We can see that RandomForest performs better than LGBMClassifier in the real world. It’s my first experience with LGBMClassifier, but I always works with RandomForest to solve this type of problem. I think that we can try more parameters and a better data preparation to get more results with this algorithm.

We started with understanding the data, applying techniques to handle with missing values, PCA, relevant features, etc. Then, we create some models and to finalize, we send files with predictions to get the real score from Kaggle Competition.

---

## File descriptions

- dataset_overview.html
> This file was created by pandas-profiling and it's part of my exploratory analysis.

- home-credit-default-risk.ipynb
> This Jupyter Notebook works in Kaggle Kernel and it's has all the steps that I worked on this project.

- requirements.txt
> This file has all libs necessary to run this project.

- images (folder)
> This folder contains some images of this project (graphics, etc.).

## Requirements

- Python: 3.7.x
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- os
- sklearn
- tensorflow

All dependences are available on `requirements.txt` as well.