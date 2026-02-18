This project aims to predict the sentiment of IMDB reviews. The data consists of two columns, "Review" and "Sentiment." Techniques such as TF-IDF are used to convert the Review column into vectors
of important words. Then, logistic regression (LR) and K-Nearest Neighbors (KNN) models were used to predict the sentiment of the reviews. The LR model achieved a 90% 5-fold cross-validated accuracy score, and the KNN model
achieved a 79% 5-fold cross-validated accuracy score. Visualizations showed that the KNN model struggled to neatly draw a decision boundary, demonstrating that models which leverage a global 
decision boundary, such as LR, perform better on this data. 
