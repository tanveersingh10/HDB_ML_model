# HDB_ML_model

In this project I tried to create a regression model that could accurately predict the resale price of HDB apartments in Singapore. I obtained the dataset from the government's website data.gov.sg

# Features of the project

- Comprehensive Data Preprocessing: The project starts by cleaning the dataset and converting categorical data into numerical representations.
- Feature Extraction and Dimensionality Reduction: I performed feature extraction and PCA to reduce the dimensionality of the data and focus on the most influential factors affecting resale price.
- Data Standardization: The data was standardized using Scikit-Learn's Standard Scaler to achieve zero mean and unit variance. This ensures all features have equal weightage and speeds up the convergence of the machine learning models.
- Model Training and Evaluation: The preprocessed data was split into training and test sets, and the models were trained and evaluated accordingly. Metrics such as Mean Squared Error (MSE) and R-squared were used to evaluate model performance.
- Hyperparameter Tuning: A grid search approach was used to fine-tune model hyperparameters. This ensures that the models perform at their peak potential.
- Cross-Validation: I employed cross-validation techniques to check the robustness of our models. This gives a more realistic understanding of how well the models would generalize to unseen data. 

# Usage
To clone and run this application, you'll need Git and Python installed on your computer. From your command line:

git clone https://github.com/tanveersingh10/HDB_ML_model

cd HDB_ML_model

pip install -r requirements.txt

jupyter lab hdb_model
