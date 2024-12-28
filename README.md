Credit Card Fraud Detection Using Logistic Regression
Overview
This project aims to detect fraudulent credit card transactions using logistic regression. The dataset contains credit card transactions made by European cardholders in September 2013, and the goal is to build a model that can effectively classify transactions as legitimate or fraudulent.

Dataset Information
The dataset includes 31 columns:

Time: Number of seconds elapsed between this transaction and the first transaction in the dataset

V1 to V28: Principal components obtained from PCA

Amount: Transaction amount

Class: Target variable (0 for legitimate, 1 for fraudulent)

Project Structure
creditcard.csv: The dataset file.

credit_card_fraud_detection.ipynb: Jupyter Notebook with the complete workflow.

Requirements
Python 3.x

pandas

numpy

scikit-learn

matplotlib

seaborn

Install the required packages using:

bash
pip install pandas numpy scikit-learn matplotlib seaborn
Steps to Execute
Import Modules:

Import necessary libraries for data manipulation, visualization, and model building.

Load the Dataset:

Load the dataset into a pandas DataFrame and inspect the first few rows.

Data Preprocessing:

Check for missing values and handle them using the forward fill method.

Exploratory Data Analysis (EDA):

Visualize the distribution of the target variable (Class) and other features.

Model Training:

Split the data into training and testing sets.

Train a logistic regression model on the training data.

Model Evaluation:

Evaluate model performance using accuracy and classification report on both training and testing sets.

Usage
Clone the repository:

bash
git clone https://github.com/RAGUL1531/Credit-Card-Fraud-Detection/blob/main/Requirements.txt
cd credit-card-fraud-detection
Open and run the Jupyter Notebook:

bash
jupyter notebook credit_card_fraud_detection.ipynb
Results
The logistic regression model achieved the following accuracy:

Training Accuracy: 96.66%

Testing Accuracy: 89.52%

Conclusion
The logistic regression model performed well in detecting fraudulent transactions, demonstrating its effectiveness in binary classification tasks. Further improvements can include trying different algorithms or hyperparameter tuning for even better results.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
The credit card fraud detection dataset is provided by Kaggle.

Special thanks to the open-source community for providing the tools and libraries used in this project.