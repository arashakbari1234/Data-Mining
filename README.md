# Data-Mining
Computer assignments of "Data Mining" Course ar University of Tehran

The course had three main exercises or mini-projects:
## 1- Exploratory Data Analysis
Download Blood Transfusion Service Center Data Set from UCI Machine Learning Repository and run a full Exploratory data analysis and data visualization on it. Check number of features and create box plots and acatter plots in order to analize the dataset.
Find out which feature is best candidate for data classification.
## 2- Classification and Principle Component Analysis
  ### Part 1 (Maternal Health Risk Data Set Data Set): 
  Load the dataset and divide it into features and labels. Encode the labels in order to change categorical data to ordinal nubmers.
  Shuffle the data and split it into train and test sets with 70% to 30% ratio. Implement data preprocessing it it's necessary.
  Implement classification with each of these models: Decision Tree, KNN, SVM, Random Foret. Find out the best parameters of these models with cross validation and print confusion matrix for each model.
  ### Part 2 (Parkinson's Disease Classification Data Set): 
  Implement all the tasks of Part 1. Use PCA for feature extraction and train models on new features. Find out the best PC value and their the effect of number of PCs on the accuracy of models.
## 3- Multilayer Perceptron and Clustering
  ### Part 1 (MLP): 
  fetch teh data from lfw_people dataset. there are at least two pictures from each person. Use persons who have at least 150 pictures. After loading the data, consider 25% of them for test set.
  Use PCA for feature reduction and train the Multi-layer Perceptron to classify the data. Evaluate your model and represent the confusioan matrix. 
  ### Part 2 (Clustering):
  Three datasets are prepared for you. Load them and visualize each of them of a 2D scatter plot. Describle how clusers will be if we use Desity-Based Clustering. Specify the best number of clusters.
  Use the Lloyd(k-means) algorithm and cluster the data. choose the K centers from x_1,...,x_n(dataset). Find the best K for each of the three datasets. Report the SSE error. Use elbow method to find the best K. 
  Use fuzzy c-means algorithm and find the best K value. 
  Use DBSCAN algorithm for the datasets and report the conlustion.
