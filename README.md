<h2>Airline_Passenger_Satisfaction</h2>


<h3>Abstract</h3>
This project worked on a dataset that contains an airline passenger satisfaction survey. The project aimed to build classification models to predict passenger satisfaction and identify which model is outperformed based on accuracy. We have trained our models using DecisionTreeClassifier it performs 94% of accuracy and also we used Neural Networks it is also  performed well with 95% of accuracy.
Also we segment the customers we got extracted 5 clusters using K-Means algorithm

<h3>About Dataset :</h3>

We used a dataset of Airline Passenger Satisfaction survey from kaggle contain customers satisfaction (target variable) and various survey ratings, which contains 103904 rows and 25 features.

<h3>Methodology</h3>

1.Data Analysis and Exploration
  Here we done Analysis of dataset like Target feature visualization,shape of data,outlier detection, duplicates detection,etc..

2.Feature Engineering
 Here we resolved outliers,also done label encoding and Scaling data using Standard Scaler

3.Feature Selection
 Here we used pearson correlation technique for numerical data and Chi2 test for categorical data

4.Feature Extraction(Dimensionality Reduction)
Here we used PCA technique for feature extraction in the view of clustering.

<h3>Models And Algorithms Used:</h3>

Here we used different techniques for model building.

1.DecisionTreeClassifier

      Decision Tree performs well and gives accuracy about 94%.

2.NeuralNetworks(ANN)

     Here we used ANN for our model which gives 
      Accuracy 95%
      Validation accuracy 94%

3.Clustering using K-means
    Here we segmented the 5 clusters using ElBow method For that we Extracted Clusters using K-means K value = 5  


<h3>Tech Stack :</h3>

Languages:

          Python

Libraries:

1.Numpy and Pandas for data manipulation.
2.Matplotlib and Seaborn for plotting.
3.Sklearn for machine learning and statistical modeling.
4.Tensorflow for Neural Networks
5.Yellowbrick for Elbow method visualization.

Tools :

         1.Jupyter NoteBook
