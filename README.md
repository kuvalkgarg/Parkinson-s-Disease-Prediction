# Parkinson's Disease Prediction
This project aims to detect Parkinson's disease using machine learning techniques, in this case, a Support Vector Machine (SVM) model. It analyzes various vocal features extracted from speech recordings to classify whether a person has Parkinson's disease or not. The dataset used in this project is the "parkinsons.csv" dataset, which contains voice measurements of individuals with and without Parkinson's disease.

# Languages and Frameworks/Libraries
The project is implemented in Python, using the following frameworks/libraries:

* **numpy**
* **pandas**
* **scikit-learn**

# Installation and Execution
To run the project locally, follow these steps:

1. Clone the repository
2. Install the required dependencies:
```
pip install numpy pandas scikit-learn
```
3. Navigate to the project directory
4. Run the notebook by executing all cells at once, or run each cell individually as per your requirement

# Configuration
1. Prepare the dataset:
    * Download the "parkinsons.csv" dataset.
    * Place the dataset file in the project directory.

2. Run the project:
    * Execute the "model.py" script to train and evaluate the machine learning model.
    * The script will load the dataset, preprocess the data, train the model, and evaluate its performance.

3. Interpret the results:
    * The script will output the accuracy score of the model, indicating its performance in detecting Parkinson's disease.

# Conclusion
In this project, we developed an SVM model to detect Parkinson's disease based on vocal features extracted from speech recordings. The model achieved a high accuracy score, demonstrating its potential as a diagnostic tool for Parkinson's disease. Further improvements and refinements can be made to enhance the model's performance and extend its applications, along with implementation of other algorithms to test which model performs the best.
