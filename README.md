# Online Fraud Payment Detection using Machine Learning

This project implements a machine learning model to detect fraudulent transactions in online payments. The system analyzes various transaction features to classify whether a payment is fraudulent or legitimate.

## Dataset

The project uses the PaySim synthetic dataset, which simulates mobile money transactions based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The dataset can be found on Kaggle:

[PaySim Mobile Money Transactions Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1?resource=download)

### Dataset Features

- `type`: Type of transaction (CASH_OUT, PAYMENT, CASH_IN, TRANSFER, DEBIT)
- `amount`: The amount of the transaction
- `oldbalanceOrg`: Original balance before the transaction
- `newbalanceOrig`: New balance after the transaction
- `isFraud`: Target variable indicating whether the transaction is fraudulent (1) or not (0)

## Implementation

The project is implemented in Python using Jupyter Notebook and includes:

1. Data preprocessing and exploration
2. Feature engineering
   - Transformation of categorical features
   - Label encoding for transaction types
3. Model training and evaluation
   - Dataset splitting into training and test sets
   - Classification model implementation

## Requirements

- Python 3.x
- Jupyter Notebook
- Required libraries:
  - numpy
  - pandas
  - scikit-learn

## Usage

1. Clone this repository
2. Download the dataset from Kaggle (link provided above)
3. Open `payment_detection.ipynb` in Jupyter Notebook
4. Run the cells sequentially to:
   - Load and preprocess the data
   - Train the model
   - Evaluate the results

## Project Structure

```
├── README.md
├── payment_detection.ipynb    # Main Jupyter notebook containing the analysis
└── requirements.txt          # Python dependencies
```

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Dataset provided by PaySim on Kaggle
- Inspired by real-world financial transaction systems 