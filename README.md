# iris-flower-classification
iris flower classification model i.e  setosa, versicolor ,virginica
 Iris Flower Classification using Random Forest Classifier:
 
  Project Overview:
This project uses Random Forest Classifier to classify the famous Iris dataset into three species:

-> Iris-setosa

-> Iris-versicolor

-> Iris-virginica

The classification is based on flower measurements:

>> Sepal Length

>> Sepal Width

>> Petal Length

>> Petal Width

The goal is to train a machine learning model that can predict the species of an iris flower given these measurements.

📂 Dataset
The dataset used is Iris.csv, containing:

150 samples

4 numerical features

1 categorical target (Species)

No missing values, clean and ready for modeling.

Columns:

Id (dropped during preprocessing)

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Species

🛠 Technologies Used
Python 
Pandas
NumPy
Matplotlib
Seaborn
scikit-learn

 Steps Performed:
 
1> Importing Libraries

2> Loading the Dataset

3> Exploratory Data Analysis (EDA)

4> Scatter plots & pairplots

5> Class distribution visualization

6> Data Preprocessing

7> Dropping unnecessary columns (Id)

8> Checking for duplicates

9> Splitting into training & testing sets

10> Model Training

11> Random Forest Classifier

12> Model Evaluation

13> Accuracy score

14> Testing with New Data

Model predictions on unseen measurements.

>>>> How to run the model on other machines: 

# Install dependencies
pip install -r requirements.txt

# Run the project
python iris_classification.py
📈 Model Performance
Accuracy: ~100% (due to the simplicity and cleanliness of the Iris dataset)

Confusion Matrix: Perfect classification on test set

 Example Prediction
Input:

python
Copy
Edit
[5.1, 3.5, 1.4, 0.2]  → Iris-setosa  
[6.0, 2.9, 4.5, 1.5]  → Iris-versicolor  
[6.5, 3.0, 5.5, 2.0]  → Iris-virginica  
Output:

yaml
Copy
Edit
Test Predictions:
Measurements: [5.1, 3.5, 1.4, 0.2] → Predicted Species: Iris-setosa
Measurements: [6.0, 2.9, 4.5, 1.5] → Predicted Species: Iris-versicolor
Measurements: [6.5, 3.0, 5.5, 2.0] → Predicted Species: Iris-virginica

# Future Improvements: 
While Trying with other different ML models like (Logistic Regression, SVM, KNN, Decision Tree) the accuracy was ~100%.

Deploy as a web app using Flask or Streamlit

Add hyperparameter tuning for Random Forest
