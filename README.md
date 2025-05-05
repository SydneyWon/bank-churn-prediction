# Bank Churn Prediction
This notebook builds a machine learning model to predict whether a customer will churn (leave the bank) based on demographic and account-related features. 


## Project Highlights

- Built an end-to-end classification pipeline using Python and scikit-learn
- Identified critical features contributing to churn
- Detected and analyzed potential data leakage from the `Complain` feature
- Compared model performance with and without `Complain` to assess robustness
- Visualized feature impact using confusion matrices and metrics breakdown


## Key Learnings

- The model initially achieved 100% accuracy, precision, and recall — but further analysis revealed this was due to an overreliant feature: `Complain`.
- Removing `Complain` led to a drop in performance (Accuracy ↓ to 87%, Recall ↓ to 45%), exposing its dominant influence.
- This emphasizes the importance of identifying misleading features and avoiding overfitting or data leakage in real-world deployments.


## Tech Stack

- Python, pandas, numpy
- scikit-learn (Random Forest Classifier)
- matplotlib & seaborn for visualization


## Dataset

- Source: [Kaggle – Bank Customer Churn](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)


## Contact

Created by Sydney Won  
📧 sydney.b.won@gmail.com 
