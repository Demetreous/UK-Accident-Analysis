# UK-Accident-Analysis

## Description

Car accidents have always been a major issue and with increasing population and developing cities, the issue has been growing as well. The most important aspect of any accident is its severity because it impacts people’s lives the most. This study helps to determine the important attributes that lead to major accidents (fatal) and try to predict conditions that may lead to fatal crashes so they can possibly be prevented. The findings were made clear through various visualizations including but not limited to bar charts, pie charts, line charts, heatmaps, and scatterplots.

## Dataset

This dataset was sourced from Kaggle and consists of four files providing detailed road safety data about the circumstances of personal injury road accidents in the United Kingdom from 2005 to 2014. The dataset had a size of 1,640,597 rows over 32 columns with two additional data files and one file containing the metadata (xls file with multiple sheets explaining the data). The data required cleaning in the form of combining the different files of the dataset as well as handling missing values. There were originally 32 attributes although we decided to use feature engineering to combine or remove certain redundant or irrelevant featurs. We also took steps to handle any outliers found in the data. The data also has a class imbalance so various techniques were employed in order to negate any potential bias later on.

Link: https://www.kaggle.com/datasets/benoit72/uk-accidents-10-years-history-with-many-variables?resource=download

## Related Works

### 1. Enhancing prediction and analysis of UK road traffic accident severity using AI: Integration of machine learning, econometric techniques, and time series forecasting in public health research.

A similar study which improved their logistic regression model using Generalized Methods of Moments (GMM) to make assumptions about the entire distribution as well as Vector Autoregressive Model (VAR) to make an accurate time series forecasting. Their study shows that their models accurately predict accident severity based on features such as weather, light, road conditions, etc.

Link: https://www.sciencedirect.com/science/article/pii/S240584402404578X?via%3Dihub

### 2. A study on road accident prediction and contributing factors using explainable machine learning models: analysis and performance

This study used a set ML models to predict road accident severity in New Zealand. Some of the ML models they used include Random Forest (RF), Decision Jungle (DJ), Adaptive Boosting (AdaBoost), etc. They found that RF model has the most accuracy out of the rest of ML models as well as finding that road category and number of vehicles involved in an accident significantly impacts injury severity.

Link: https://www.sciencedirect.com/science/article/pii/S2590198223000611
