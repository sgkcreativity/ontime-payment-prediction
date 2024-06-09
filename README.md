# ontime-payment-prediction
on-time-loan-payments-predictions

This project is focused on building and training an AI/ML model to predict on-time loan payments. The project includes data preprocessing, model building, model training and evaluation steps using Python libraries. The following algorithms were evaluated: 1. Naïve Bayes classifier; 2. Random Forest Classifier; 3. Support Vector Classifier (SVC); 4. Logistic Regression; and 5. Decision Tree Classifier; 

The final model that performed better was the Random Forest Classifier. This model was finally selected and used for predicting unseen data.

## Project Structure

on-time-loan-payments/
   ```
│
├── data/
│ ├── unseenData.csv # Unseen data for model evaluation
│
├── models/
│ ├── random_forest.joblib # Trained Random Forest model
│ ├── rf_clf.pkl # Pickle file of the trained model
│
├── notebooks/
│ ├── AllModels_Workbench_WithLoanHistory.ipynb # Jupyter notebook with the entire workflow
│
├── results/
│ ├── PredictedValues_900V2.csv # Predictions on unseen data
│ ├── ontimePayments.png # Decision tree visualization
│
├── .gitignore # Git ignore file
├── requirements.txt # Python dependencies
└── README.md # Project documentation
   ```

## Installation

To run this project, ensure you have Python 3.9 installed. You can install the required packages using:

pip install -r requirements.txt

## Usage
Clone the repository:

git clone https://github.com/yourusername/on-time-loan-payments.git
cd on-time-loan-payments

## Installation

To run this project, ensure you have Python 3.9 installed. You can install the required packages using:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/on-time-loan-payments.git
    cd on-time-loan-payments
    ```
2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook to see the workflow and results:
    ```bash
    jupyter notebook notebooks/AllModels_Workbench_WithLoanHistory.ipynb
    ```
## Run the Jupyter notebook to see the workflow and results:

jupyter notebook notebooks/AllModels_Workbench_WithLoanHistory.ipynb

## Project Files
- data/training_dataset.csv: The dataset used to train the model.
- data/unseenData.csv: Unseen data used to evaluate the model.
- models/random_forest.joblib: The trained Random Forest model saved as a joblib file.
- models/rf_clf.pkl: The trained Random Forest model saved as a pickle file.
- notebooks/AllModels_Workbench_WithLoanHistory.ipynb: Jupyter notebook containing the entire model building and training process.
- results/PredictedValues_900V2.csv: The predicted values on unseen data.
- results/ontimePayments.png: Visualization of the decision tree used in the model.

## Requirements
- Python 3.9
- scikit-learn
- pandas
- numpy
- matplotlib
- graphviz
- pydotplus

## Contributing
If you would like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
The project is based on data and inspiration from various public datasets and research papers on loan payment prediction.
