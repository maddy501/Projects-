
                                                Data Analysis Projects

=>**Exploring the Data Scientists**:
This projects involes using python libraries to perform Data Analysis on the Data Scienctist data collected by Kaggel. In 2017, Kaggle (a data science community and competition platform) conducted a survey on a large range of users registered as the data scientist in their platform. The survey data are broadly covered the skill set of the data scientists, the demographic of the data scientists, the feedback of the platform and many other information.This project involved
-dealing with missing values in the dataset
-Performing Calculation among the DataFrame columns
-merging two excel dataframes using pandas
-Outlier Detection using boxplot
-Finding Data Statistics
-Plotting Stacked and simple bar graph
-Performing tokenize on text column to find the most common words that in jobs posted for data scientists.


=>**Evolution of Linux OS**: 
The projects involves data analysis on the history of kernel development of almost 13 years (early 2005 - late 2017) using python libraries. The dataset used is taken from a git log file.This project involved:
-Loading a git log file using python and overview of the data
-Using groupby and aggregation function finding the top 10 values of a column
-Converting columns to date_time format and corrrecting wrong time stamps.
-Visualising the result using matplotlib graphs


                                                Machine Learning Projects

 
=> **Clustering&PCA**: Perform Unsupervised k means clustering to design an environment to predict a class/category from a dataset based on specific features of that class. However, all the features are not strong enough or in other words features not that much variance/uniqueness across the classes. So clustering model needs to be designed. Following steps were performed:
- Loading the dataset into a pandas dataframe
- Scaling of the dataset
- Seperating features from labels
- Implement K means Clustering 
- Plot Elbow Plot to find the actual number of classes in the dataset
- Write a function to calculate purity score of the clusters
- Implement  k-means clustering for different distance metrics using pyclusteting library and find purity score
- Find the best metrics based purity score
- Use selection criteria (ANOVA, Chi-squared) to select best three features and use them for K-Means clustering
- Implement PCA on the dataset
- Plot captured variance with respect to increasing latent dimensionality

=>**Book Recommendation Based On Text Classification**
The purpose of this project was the recommendation of a new book to a reader based on the content of the previous book a reader read. The whole content of each book was converted into tokens. Stop words were removed from the tokens and then the stemming process was implemented on the tokens. A tf-idf model (term frequency-inverse document frequency) was then implemented to define the importance of each word depending on how frequent it is in this text and how infrequent it is in all the other documents. As a result, a high tf-idf score for a word will indicate that this word is specific to this text. Furthermore, Cosine similarity was then implemented to find the pairwise difference between each book from the other book. Lastly, the result was visualized using a dendrogram to show the recommended books after reading a specific book. The data set used for this project was a list of all books written by Charles Dickens available at Project Gutenberg.

=>**Forcasting temperature based on yearly weather data**: 
Environment and its changes are the most complex system.The dataset contains total 10 features. Each row contains an hourly record of weather status and the data was recorded for the time period between 2006 and 2016.This project implements Linear Regression to predict temperature and implement Logistic Regresion to predict class label for precipitation type.  Following steps were performed:
- Loading the dataset into a pandas dataframe
- Draw a heat map to find insignificant features for predicting temperature
- Remove insignificant features
- Seperating Features and Labels
- Divide data into Train and Test in 70/30 ratio
- Implement Linear Regression and calculate Accuracy
- Create a regularised Regression model by implementing Ridge Regression, Grid Search CV, kfold Cross validation and calculate accuracy
- Implement Logistic Regression to predict Precipitation Type Columns class label
- Discuss the test performance using precision, recall and confusion matrix

=>**Classification model to predict the approval of a credit card application**
The aim of the project was to overcome the task of manually analyzing the credit card applications and using the power of machine learning to create an automatic credit card approval predictor using ML techniques. The data set used for this project was taken from Credit Card Approval Dataset from the UCI Machine learning Repository. The dataset was anonymized for confidentiality purposes. This project involved loading the data, filling the missing values using means for numerical columns, and most frequent values for categorical columns. Moreover, the categorical columns were then converted to numerical using One hot encoder. The numerical columns were also standardized between 0 and 1. The data set was then split in train and the test split and logistic model was then implemented. To improve the accuracy of the model a regularized logistic model was then created using hyperparameter tuning and 5-fold cross-validation. The classification accuracy of the model was recorded as 85%. A classification report and confusion matrix was also created to better understand the results.

=>**Categorization of invoices into categories(Salary,food,Traveling) using Natural Language Procsssing**
Most of the companies spent loads of money at various places like employee salaries, buying raw materials, transport etc which makes it difficult to manually catogorise each invoice in a relevant category. This helps later as the company would know where did they spent the most amount of the money. This project involces loading a dataset of Text invoices using pyhon. Performing text processing by removing stop words and perform stemming and lemitization. Features are then seperated from the class labels(Salary, food, raw material etc) and the dataset is divided into test and train set in 70/30 ratio. Then CNN, sequential model with LST layerand RNN models are implemented to perform Text Classification and accuracy is noted for each of the model. All three models use loss='categorical_crossentropy', optimizer='adam', metrics as accuracy. Graph for accuracy and loss are plotted and the model is fit for certain amount of epochs. Accuracy of the model is calculated on the test set. RNN model records the highest Text Classification accuracy of 89.45%.
