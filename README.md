# Big_Data_Analytics_Project

# METHODS FOR TACKLING COLD START PROBLEM IN RECOMMENDER SYSTEMS

## Introduction
This repository aims to propose a pertinent technique to tackle cold start problem in recommender systems related to Big Data. By employing the desired dataset and a blend of techniques and tools like collaborative filtering, content based filtering and matrix factorization, our motive is to offer practical solutions to improve the precision and effectiveness of recommendation system. 

## Project Methodology

### Data Acquisition
A proper dataset selection is the most vital part of a research. There are a massive source of datasets available online. "MovieLens" dataset is sourced and selected froma open source as seemed to be more aligned with the project preference. This dataset is selected due to its relevance, richness of data, availability, scalability, and applicability to address the cold start problem. We are going to illustrate a project that recommend movies in different ways. As such, the selected dataset consists of comprehensive and diverse set of movie ratings, combined with the associated user and item metadata. Public access to the dataset is available and can be viewed or accessed using this link: https://grouplens.org/datasets/movielens/


### Data Processing and Analysis
In this step, we will utilize the MovieLens Latest Small dataset and merge related datasets for research ease. The following step is cleaning and processing the merged data to address outliers and handle missing values. We will then focus on addressing new attributes if there is any. 

### Model Design
In this step, primarily the idea of leveraging the behavior of others will be used to refine the recommendation outcomes. The reason its called “collaborative Filtering”  is it will recommend stuff based on other peoples’ collaborative behavior. 

We will also implement most simple approach recommending items just based on the attributes of those items themselves, instead of trying to use aggregate user behavior data. This approach is known as “Content Based Filtering”. 

As we all know that each algorithm has its own strengths and weaknesses. We will combine both collaborative filtering and content based filtering and calling it a hybrid approach. This approach will eliminate minimalist errors and will provide overall accuracy. 

### Model Evaluation
We will evaluate and compare each techniques individually using Root Mean Square Error (RMSE) and Mean Absolute Error (MAE) 

## Results and Discussion
The results will be critically analyzed and compared addressing research motive. 

## Tools
Python 3 is the primary tool thats used. Download Link for python 3: https://www.python.org/downloads . Google Colab is also used as supporting tool. Python package that makes developing recommender systems easier, called “Surprise” is also used.

## Github Repository
Github repository link: https://github.com/abdurmahbub123/Big_Data_Analytics_Project
