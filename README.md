# Machine Learning Project : Iris-flower-classification
This program applies basic machine learning concepts on *Fisher's Iris Data* to predict the species of a new sample of Iris flower.

**Software and Libraries**
- Python 3.9.5
- scikit-learn 0.24.2

**Introduction**  
The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Iris). The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.
- The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
- Four features were measured from each sample (in centimetres): 
  - Length of the sepals
  - Width of the sepals
  - Length of the petals
  - Width of the petals

**Working of the iris_decision_tree_classifier**
- The program takes data from the `load_iris()` function available in `sklearn` module.
- The program then creates a decision tree based on the dataset for classification.
- The user is then asked to enter the four parameters of his sample and prediction about the species of the flower is printed to the user.

**Working of the iris_selfmade_KNN**
- The program takes data from the `load_iris()` function available in `sklearn` module.
- The training sample space is used to train the program and predictions are made.
