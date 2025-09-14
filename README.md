🔍 Project Overview

Cervical cancer remains a global health challenge, but with the right tools, we can shift the narrative from late detection to proactive prevention. This project takes a dataset of patient records and applies machine learning techniques to classify whether an individual is at risk.

The workflow includes:

1. Data Cleaning – Handling missing values (? → NaN) and separating categorical vs. numerical features.

2. Balancing the Dataset – Using SMOTE to address the heavy class imbalance.

3. Feature Engineering – Selecting meaningful variables that capture lifestyle, reproductive history, and exposure to STDs.

4. Model Building – Training and comparing multiple models:

Logistic Regression

Decision Tree & Random Forest

Bagging & Boosting (AdaBoost, GradientBoosting)

KNN & Naive Bayes

5. Evaluation – Measuring performance with accuracy and F1-score, since precision/recall balance is crucial in healthcare.

📊 Results at a Glance

While accuracy tells one story, the F1-score was particularly important here due to the skewed dataset. Ensemble methods (like Random Forest and Gradient Boosting) outperformed simpler models, showing promise for real-world deployment where reducing false negatives is critical.

🚀 Why This Matters

i. Healthcare Impact: An ML-assisted system could help doctors flag high-risk patients earlier.

ii. Learning Opportunity: This project demonstrates how to handle imbalanced data, apply ensemble learning, and evaluate models responsibly.

iii. Future Scope: With richer datasets (including genomic data, pap smear images, etc.), this work could evolve into a full-fledged clinical decision support system.

🛠️ Tech Stack

i. Python

ii. Libraries: NumPy, Pandas, Scikit-learn, Imbalanced-learn, Seaborn, Matplotlib

📌 How to Run

1. Clone the repo.

2. Place cervical.csv in the working directory.

3. Run the Jupyter Notebook:

jupyter notebook cervical_cancer_prediction.ipynb


4. Follow along with preprocessing, model training, and evaluation.

💡 Takeaway

This isn’t just about code or algorithms. It’s about using data science for social good—bridging the gap between raw data and meaningful healthcare insights.
