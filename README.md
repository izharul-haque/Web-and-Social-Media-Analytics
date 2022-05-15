# Web-and-Social-Media-Analytics

This is a NLP project for Web and Social Media Analytics

Dataset available: http://jmcauley.ucsd.edu/data/amazon/index_2014.html

## Problem Statement

Customer is a mobile manufacturer based in the US, who entered the market three years ago. As a new entrant in the sector, they want to understand their competitors and preferences of their users so that they can design their strategies accordingly.They want to tweak the marketing strategies to add more value to their brand, provide features to customers that add the most value, and close the demand-supply gap. Their objective is to increase the market share as well as the brand value.

## Objective

### Product Development And Marketing Strategies
- Development of features that have high utility value for the customers
- User experience with the current devices
- Strength and weaknesses of competitors
- Market share of the competitors
- Pricing strategies based on features, utility and competitor's pricing strategies

## Solution:

### The solution has been divided into two parts.
Part 1: Deriving the business insights that are useful for product development and marketing.
Part 2: Creating a sentiment classification engine.

Steps 1 to 3 discussed below form the first part of the solution and step 4 constitutes the second part. 
- Step 1: Data pre-processing
- Step 2: Text analytics
- Step 3: Visualisation and storytelling
- Step 4: Building a sentiment classification engine

### Number of customer reviews per year
![image](https://user-images.githubusercontent.com/76435558/167936319-db08a089-606a-43d6-b081-b2c506eca6d6.png)

### Top 10 Brands Price Distribution
![image](https://user-images.githubusercontent.com/76435558/167936805-e50efc6e-ea3a-492a-a1c7-49136c00b33b.png)

### Reviews Price Distribution Wise
![image](https://user-images.githubusercontent.com/76435558/167937454-3d1cdafa-e169-4490-a256-aafb3676d447.png)

## Data Science Model
Our goal was to use Naive Bayes for text classification for sentiment analysis of the reviews and helps in faster decision making.

## Model Evaluation
We used sensitivity- specificity and precision-recall matrix for the model.

## Results
The application of random oversampling model has resulted in an equal distribution of the binary labels. This has resulted in a jump in specificity by 0.23 with a slight decrease in the sensitivity by 0.08.

### Models accuracy,sensitivity,specificity on train and test dataset are :
- Train dataset :accuracy(87%),sensitivity (95%),specificity(64%)
- Test Dataset : accuracy(86%),sensitivity (95%),specificity(59%)

### Models precision,recall,F1 score on train and test dataset are :
- Train dataset :precision(88%),recall (95%),F1 score(92%)
- Test Dataset : precision(87%),recall (95%),F1 score(91%)
- Area under curve : 90%
- Hence, we can conclude that this model is good.

## Tech
The following technologies were used for this part of the project:
- Python 3
- Jupyter Notebook
- Pandas: Python package for data analysis
- Numpy: Python package for numerical analysis
- Scikit-learn: Python package for predictive analysis
- Matplotlib and Seaborn for plotting graphs
