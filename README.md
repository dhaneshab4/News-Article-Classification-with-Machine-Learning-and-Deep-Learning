# News-Article-Classification-with-Machine-Learning-and-Deep-Learning

This project implements a machine learning pipeline to classify news articles into different topical categories. It uses various machine learning models like Logistic Regression, K-Nearest Neighbors (K-NN), and a Deep Learning Model (LSTM). The key steps include data understanding, preprocessing, modeling, and evaluation. The goal is to achieve high accuracy in classifying articles based on the text data provided.

# Project Structure

**1. Data Understanding**

* Load and explore the dataset.
* Analyze the most common terms in each category.
* Evaluate the sentence lengths and detect outliers or missing values.

**2. Data Preparation and Modeling**

* Split the dataset into training, validation, and test sets.
* Preprocess the data by cleaning text, lowercasing, removing punctuation, and tokenizing.
* Train Logistic Regression, K-NN, and a Deep Learning (LSTM) model.

**3. Model Evaluation**

* Evaluate models based on accuracy, precision, recall, and F1-score.
* Perform error analysis and improve model performance through hyperparameter tuning and retraining.
* Cross-validate the models and apply them to the test set.
# Setup Instructions
**1. Clone the Repository:**
```bash
git clone https://github.com/dhaneshab4/News-Article-Classification-with-Machine-Learning-and-Deep-Learning.git
cd News-Article-Classification-with-Machine-Learning-and-Deep-Learning
```
**2. Install Required Packages:**
```bash
pip install -r requirements.txt
```
**3. Load and Preprocess Data:**

Upload the 11.csv Dataset to Google Drive, Preprocess the data by running the Jupyter Notebook ML_Assignment.ipynb. The notebook loads the dataset, splits it into training/validation/test sets, and preprocesses it for model training.

**4. Model Training:**

Train the models by executing the sections of the notebook for each classifier:

* Logistic Regression
* K-NN
* Deep Learning (LSTM)
The training process will save the models into .pkl and .h5 formats for reproducibility.

**5. Evaluation:**

Evaluate the performance of each model on the validation and test datasets by executing the evaluation section in the notebook. The results include accuracy, precision, recall, and F1-score.
