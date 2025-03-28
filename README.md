# Credit Card Fraud Detection using Ensemble Learning

## Overview
This project focuses on detecting fraudulent credit card transactions using ensemble learning techniques. It leverages multiple machine learning models to enhance prediction accuracy and reduce false positives.

## Dataset
The dataset used for this project contains credit card transactions, including both fraudulent and legitimate transactions. The dataset is highly imbalanced, requiring appropriate techniques to handle class distribution.

## Features
- **Data Preprocessing:** Handling missing values, feature scaling, and encoding categorical variables.
- **Exploratory Data Analysis (EDA):** Visualizing transaction patterns and fraud distributions.
- **Feature Engineering:** Creating new features to improve model performance.
- **Model Training:** Implementing ensemble learning techniques including:
  - Random Forest
  - Gradient Boosting (XGBoost, LightGBM, CatBoost)
  - Voting and Stacking Classifiers
- **Model Evaluation:** Assessing models using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
- **Hyperparameter Tuning:** Optimizing models using Grid Search and Random Search.

## Installation
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CreditCardFraudDetection.git
   cd CreditCardFraudDetection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook CreditCardNew.ipynb
   ```

## Usage
- Load and preprocess the dataset.
- Train and evaluate different ensemble learning models.
- Analyze model performance and make predictions on new transactions.

## Results
- The ensemble models significantly improve fraud detection accuracy while minimizing false positives.
- AUC-ROC scores demonstrate the effectiveness of ensemble learning in imbalanced data scenarios.

## Future Improvements
- Implement deep learning techniques for fraud detection.
- Enhance feature engineering with domain-specific insights.
- Deploy the model using Flask or FastAPI for real-time fraud detection.

## Contributing
Feel free to contribute by submitting issues or pull requests. Ensure your contributions align with the project's goals.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries, please contact:
- **Avinandan Bose** 
- GitHub: [Avinandan Bose](https://github.com/AvinandanBose/)


