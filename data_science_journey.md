# Data Science Journey

## Business Understanding / Domaine Understanding

## Data Understanding
- Get familiar with the data and gain insights / intuition
- Explanatory Data Analysis / evaluate data quality
- Scripts: .ipynb (Jupyter Notebook)
- Tools: Tableau, PowerBI

## Data Preparation
- Extract
    +

- Transform
    + uni- and multivariate descriptive statistics and plots
    + clean the data on the back-end (database):
        * remove duplicates, treat outliers and deal with incorrect/corrupt and missing data
        * detect by distribution curve and other plots
        * replace them by mean or median values
        * introduce a dummy variable whether data is missing or not
    + Scripts: data_preperation.py

- Load to database
    + check number of rows (top & bottom)
    + check value types (dates and currencies)
    + check text values


## Feature Engineering
- transform the prepared data to be compatible with the modelling requirements
- brainstorm, test, create potential features
- split the data into training, validation and test set

## Modelling
- Regression techniques:
    + Multiple Linear Regression (MLR),
    + Support Vector Regression (SVR),
    + Decision Tree Regression (DTR),
    + Random Forest Regression (RFR)

- Classification techniques:
    + Log regression
    + Decision tree
    + Random forest,
    + K-Nearest Neighbor,
    + Naive Bayes

- Clustering techniques:
    + k-means,
    + hierarchical clustering

- Neural networks and deep learning

- Reinforcement Learning
    + exploration & exploitation
    + eg. multi-armed bandit problem
    + upper-confidence bound algorithm UCB
    + Thompson sampling

## Evaluation
- Accuracy: MAE
- Precision: CV
- Speed
- Interpretability
- Residual Analysis
- Assumption tests (in case of MLR)

## Deployment
- Data visualisation
- Software: Project code in a structured, self-contained, class-based API
- Self-serve analytics: create Summary Tables for the most frequent requests:
  - Amazon Redshift: https://aws.amazon.com/redshift/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc
  - Chartio: https://chartio.com/

## Presentation
- How to present insights, communicate and organize in simple teams
- (Receiver-Directed) Communication: Communication is not what is said, but what is heard.
- Why? How? What?
- Project Pipeline for Projects: everyone can access the dashboard and post their requests, e.g. Trello Board

## Software Development
- unit tests (shrinked dataset)
- functions can be seperated into smaller ones, when they are used in other approaches
- docker (!)


# Literature
- Leo Breiman, Statistical Modeling: The Two Cultures: https://projecteuclid.org/download/pdf_1/euclid.ss/1009213726
- Nate Silver, Signaling the noise: https://www.goodreads.com/book/show/13588394-the-signal-and-the-noise?from_search=true&from_srp=true&qid=QvT5Da0CuR&rank=1


