# Netflix Churn Prediction

## Introduction

Netflix Churn Prediction is a machine learning project aimed at predicting the likelihood of subscribers to churn or cancel their Netflix subscription. By analyzing various customer attributes and historical data, we aim to build a predictive model that can identify customers at risk of churning. This project is valuable for Netflix to proactively engage with customers and reduce churn rates.

## Dataset

The dataset used in this project contains various attributes of Netflix subscribers, including subscription type, monthly revenue, join date, last payment date, country, age, gender, and device. The target variable is the plan duration, representing the length of the subscription. The dataset is provided in a CSV file named `netflix_data.csv`.

## Data Preprocessing

- Irrelevant columns such as "User ID" are removed.
- Categorical variables are encoded as dummy variables using one-hot encoding.
- Missing values are handled by filling them with zeros.

## Feature Engineering

Feature engineering involves creating new features or transforming existing ones to improve the predictive power of the model. Some potential feature engineering techniques for this project include:
- Extracting features from date columns such as "Join Date" and "Last Payment Date".
- Calculating additional metrics or ratios based on existing attributes.
- Engineering interaction features between relevant attributes.

## Model Training and Evaluation

- The dataset is split into training and testing sets using a 80-20 ratio.
- Feature scaling is performed to ensure all features have the same scale.
- A Random Forest classifier is trained on the training data.
- The model is evaluated using accuracy score, classification report, and confusion matrix to assess its performance in predicting plan durations.

## Visualization

- Feature importance is visualized using a bar plot to identify the most influential features in predicting plan durations.
- The confusion matrix is visualized using a heatmap to evaluate the performance of the model in predicting different plan durations.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/netflix-churn-prediction.git
```

2. Navigate to the project directory:

```bash
cd netflix-churn-prediction
```

3. Run the Python script `netflix-churn-prediction` using the following command:
```bash
python netflix-churn-prediction.py
```
4. Install the required Python libraries using pip:
```bash
pip install -r requirements.txt
```
Run the Jupyter notebook or Python script to train the model, make predictions, and evaluate the model's performance

##License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/usamajavaid390/netflix-churn-prediction/blob/main/LICENSE) file for details.












