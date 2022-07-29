# Markdown
1. Based on the actual quotation and transaction data of the stock, extract a series of characteristic combinations F1 such as transaction spread, quotation spread, and transaction volume; use the clustering algorithm to cluster 113 types of stocks into 7 types, and calculate the above characteristics of these 7 types of stocks Combine F2; use the KNN algorithm to find the most similar data points in time series, and calculate the feature combination F3 in the most similar time; combine the three types of features F1, F2, and F3 to get the final feature vector F.
2. On the basis of the above features, build machine learning LightGBM and neural network models, use RMSPE as the loss function, and use sklearn, lightgbm, tensorflow and other modules to build models for training, so as to achieve the effect of predicting actual volatility when given transaction data .
3. The results of the LightGBM and neural network models are equally weighted to achieve the top4% ranking.
