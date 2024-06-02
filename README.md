The Workbook contains step by step analysis and model building using Neural Networks. The initial model is improved upon with improvements to the model by adopting the following methods. 

# Neural Network Bank Churn Prediction

This project focuses on predicting customer churn in a bank using a neural network model. It involves data preprocessing, model training, and evaluation of model performance to derive actionable business insights.

## Project Overview

The goal of this project is to build a predictive model to identify customers who are likely to churn. This can help the bank in taking proactive measures to retain customers.

## Data Overview

The dataset used for this project includes various features such as customer age, tenure, balance, and activity status, among others, to predict the likelihood of a customer leaving the bank.

## Model Performance Improvement

The neural network model has been optimized using the Adam optimizer. Various preprocessing steps and hyperparameter tuning techniques were employed to enhance model performance.

## Actionable Insights and Business Recommendations

- Older customers have a higher churn rate, indicating a need for age-specific retention strategies.
- Both new and long-term customers are more likely to churn compared to those with average tenure.
- Female customers and inactive members show a higher churn rate, suggesting targeted engagement programs could be beneficial.

## Installation

To run this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/NeuralNetwork_BankChurn.git
    ```
2. Navigate to the project directory:
    ```sh
    cd NeuralNetwork_BankChurn
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Load the dataset:
    ```python
    import pandas as pd
    data = pd.read_csv('Churn.csv')
    ```
2. Preprocess the data:

  Refer to the notebook for pre-processing steps
   
3. Train the model:\
   Refer to the notebook for model train, test and validation criteria
4. Evaluate the model:\
   Refer to the notebook for model evaluation criteria

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact Information

For any questions or suggestions, please contact Vamshi Pokala, vam.pokala@gmail.com

