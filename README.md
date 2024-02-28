# Customer Churn Prediction for Bank Savings Accounts
Predicting customer churn for bank savings accounts using machine learning.

### Project Overview
This project focuses on predicting customer churn for a bank's savings account product. The objective is to identify customers likely to churn, i.e., whose account balances may fall below the minimum required balance, using demographic and transactional data.

### Data Description
The dataset encompasses various aspects of customer information, divided into three main categories:

- **Demographic Information**: Includes customer ID, age, gender, number of dependents, occupation, and city.
- **Customer Bank Relationship**: Covers the vintage of the customer with the bank, net worth category, branch code, and days since the last transaction.
- **Transactional Information**: Encompasses current balance, previous month's balance, average monthly balances in previous quarters, credit and debit amounts for the current and previous months, and churn indication (1 if the average balance falls below the minimum balance in the next quarter, 0 otherwise).

### Installation
To run this project, install the required libraries as listed in `requirements.txt`:
`pip install -r requirements.txt`

### Usage
Execute the Jupyter notebook `Bank Data Chrun.ipynb.ipynb` to follow the data analysis, preprocessing, model training, and evaluation steps. The analysis is documented in a Jupyter notebook named `Bank Data Chrun.ipynb`. 

### To view the analysis:
run: jupyter notebook `Bank Data Chrun.ipynb.ipynb`, or you can refer to the PDF file as well.

## Model File

The `final_model.joblib` file contains the trained machine learning model used for predicting customer churn. This model was trained using the Random Forest algorithm (or specify the algorithm you used) and can be loaded for making predictions without the need to retrain.

### Loading the Model

To load the model, use the following Python code:

Python
import joblib

### Load the trained model
model = joblib.load('final_model.joblib')

### Now you can use the model to make predictions
### predictions = model.predict(X_new)

### Make sure to replace `X_new with the new data that you want to predict on, ensuring it has been preprocessed in the same way as the training data.

### Results and Conclusion
Key findings and insights from the analysis will be summarized here, including the performance of the predictive model and recommendations for reducing customer churn.
The project identifies key predictors of customer churn and employs machine learning models to predict the likelihood of churn for each customer. The findings and recommendations for improving customer retention are detailed in the notebook.

## Technologies Used
- Python for data processing and machine learning.
- Pandas and NumPy for data manipulation.
- Matplotlib and Seaborn for data visualization.
- Scikit-learn for predictive modeling.

## Contact
For inquiries or further discussion, please contact me at rishabhsharma1600@gmail.com.

