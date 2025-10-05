# Machine-Learning-Project
This project applies machine learning techniques to predict  rating of movies based on various features. 

It includes exploratory data analysis(EDA). We handled the null values by dropping some values, replaced numerical datas with mean values of the column, replaced categorical values using mode of that column. Also, we scaled the datas for better performance using MinMaxScaler.

For EDA, we analyzed feature distribution using histograms, density plots and box-plots. Visualized missing-values using bar charts. Analyzed feature correlations using Pearson correlation and heatmaps. 

Moreover, transformed the categorical values into numerical ones using LabelEncoder. Splitted the dataset in 70-30 ratio where 70% was used for training and 30% for testing.

We used supervised learning models like KNN(K-Nearest Neighbors), Decision Tree, Neural Network(MLPClassifier). Also used unsupervised K-Means clustering for comparison. 

Furthermore, each of the supervised model's performance was assessed using precision score, recall score, f-1 score, support scores.

We used bar chart to compare the performance of the supervised models. Applied confusion matrices using heatmap to clearly show show how well each models were predicting. Showed ROC curves alongside AUC scores of each supervised models.
