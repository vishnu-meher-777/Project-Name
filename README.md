# CardSafe-AI:Robust Fraud Detection with Machine Learning



CardSafe-AI is a machine learning project designed to detect fraudulent credit card transactions using advanced algorithms. The project utilizes a Random Forest Classifier to identify potentially fraudulent transactions from a highly imbalanced dataset.

## Overview
This repository contains code and documentation for detecting fraudulent credit card transactions. The project includes data preprocessing, exploratory data analysis, model training, and evaluation, as well as visualization of results.

## Dataset

- File: creditcard.csv
- Description: Contains anonymized credit card transactions with features related to transactions and a binary label 
 indicating whether a transaction is fraudulent or valid.

## Columns:

- Time: Time elapsed since the first transaction in the dataset
- V1 to V28: Anonymized features derived from transaction data
- Amount: Transaction amount
- Class: Label indicating whether the transaction is fraudulent (1) or valid (0)

## Installation
To get started with the project:

Clone the repository:

    git clone https://github.com/manish3173/CardSafe-AI.git
Navigate to the project directory:


    cd CardSafe-AI
Install dependencies:


    pip install -r requirements.txt


## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter (for running Jupyter Notebooks)

## Usage
1. Launch Jupyter Notebook:

   jupyter notebook
   
3. Open the Notebook:

- Navigate to the credit_card_fraud_detection.ipynb file in the Jupyter Notebook interface.
- Open the notebook to view and run the code interactively.
  
3. Run the Notebook:

- The notebook includes cells for:
  - Loading and preprocessing the data
  - Analyzing class imbalance
  - Visualizing transaction amounts and correlation matrix
  - Training a Random Forest Classifier
  - Evaluating the model and displaying performance metrics
  - Visualizing the confusion matrix

## Analysis Results
- Accuracy: 99.96%
- Precision: 96.15%
- Recall: 79.79%
- F1-Score: 87.21%
- Matthews Correlation Coefficient (MCC): 0.88

## Visualizations

The notebook generates the following visualizations:

- Histograms of transaction amounts for valid and fraudulent transactions
- Correlation matrix heatmap
- Confusion matrix heatmap

## Contact
For questions or support, please contact:

- **Y Manish Kumar**: [ymanishk602@gmail.com](mailto:ymanishk602@gmail.com)
  
## Contributing
Feel free to submit issues and pull requests. Contributions are welcome!


## License
This project is licensed under the MIT License.
