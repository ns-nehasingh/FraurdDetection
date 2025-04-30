# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using Machine Learning and Deep Learning techniques. Various models like Logistic Regression, Random Forest, XGBoost, CNN, and GNN are applied to a highly imbalanced real-world dataset.

## Dataset
- Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Total Transactions: 284,807
- Fraudulent Transactions: 492 (~0.17%)

## Techniques Used
- SMOTE for handling class imbalance
- Ensemble learning methods
- Deep learning models (CNN and GNN)

## Libraries and Tools
- Python
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- PyTorch / PyTorch Geometric
- Pandas, NumPy, Matplotlib, Seaborn

## Folder Structure
- `fraud_detection.ipynb` – Main Jupyter notebook for model building and evaluation
- `models/` – Contains model training scripts (optional if you split later)
- `requirements.txt` – Python libraries required to run the project (to be created)

## How to Run
1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `fraud_detection.ipynb` notebook.

## License
This project is for educational and research purposes only.
