## Customer Churn Prediction
This project is about predicting customer churn using machine learning models. The dataset used in this project is a collection of telecom customer data.

## Project Description
The goal of this project is to predict whether a customer will churn based on various features such as the number of customer service calls, total day minutes, and whether they have an international plan.

## Data
The data used in this project is a collection of telecom customer data. The data includes the following columns:

- State: The state the customer resides in.
- Account length: The length of the customer’s account.
- Area code: The area code of the customer’s location.
- Phone number: The customer’s phone number.
- International plan: Whether the customer has an international plan (Yes/No).
- Voice mail plan: Whether the customer has a voice mail plan (Yes/No).
- Number vmail messages: The number of voice mail messages the customer has.
- Total day minutes: Total minutes of day calls.
- Total day calls: Total number of day calls.
- Total day charge: Total charge of day calls.
- Total eve minutes: Total minutes of evening calls.
- Total eve calls: Total number of evening calls.
- Total eve charge: Total charge of evening calls.
- Total night minutes: Total minutes of night calls.
- Total night calls: Total number of night calls.
- Total night charge: Total charge of night calls.
- Total intl minutes: Total minutes of international calls.
- Total intl calls: Total number of international calls.
- Total intl charge: Total charge of international calls.
- Customer service calls: Number of calls to customer service.
- Churn: Whether the customer churned or not (True/False).

## Methodology
The project involves several steps:

- **Data Loading and Preprocessing**: The data is loaded using pandas and preprocessed. The preprocessing steps include encoding categorical variables, splitting the dataset into training and test sets, and feature scaling.
- **Exploratory Data Analysis (EDA)**: EDA is performed to understand the distribution of the data and the relationship between different features. This includes creating histograms, box plots, and a heatmap of correlations.
- **Model Training**: A RandomForestClassifier is trained on the data.
- **Model Evaluation**: The model is evaluated based on its accuracy score.

## Results
The RandomForestClassifier model achieved an accuracy of 93%.

## Usage
To run the project, you need to have Python installed on your machine. You also need to install the necessary libraries, which include numpy, pandas, matplotlib, seaborn, sklearn.

You can run the project by executing the Python script in a Python environment.

## Contributing
Contributions are welcome. Please feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
