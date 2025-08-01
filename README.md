📊 Income Classification Using U.S. Census Data
🧠 Overview
This project explores a binary classification problem using the U.S. Census "adult" dataset, where the goal is to predict whether a person earns more than $50K/year based on demographic and employment-related features. It demonstrates an end-to-end supervised machine learning pipeline, including preprocessing, model training, and evaluation.

🎯 Objectives & Goals
Build a classification model to predict income class (<=50K or >50K)

Explore the effects of feature engineering and model selection

Compare multiple ML algorithms on real-world tabular data

Practice interpretability and ethical reflection in ML decisions

🧪 Methodology
Data source: UCI Adult Income Dataset (cleaned version)

EDA: Class balance, missing values, feature distributions

Feature engineering: One-hot encoding, normalization, categorical conversion

Models trained: Logistic Regression, Decision Tree, K-Nearest Neighbors

Evaluation metrics: Accuracy, precision, recall, F1-score

Tools used: Python, pandas, scikit-learn, matplotlib, seaborn

📈 Results & Key Findings
Best model: Logistic Regression

Accuracy: ~83%

F1-score: ~0.76

Class imbalance noted (75% earn ≤50K), so precision/recall used for better evaluation

Logistic Regression provided good performance with interpretability

📊 Visualizations
Included in the notebook.ipynb:

Class distribution bar plot

Histograms of numeric features

Model comparison summary table

🧩 Sample Dataset
A cleaned sample of the dataset is included in data/adult_sample.csv.

🧪 Notebooks & Scripts
income-classification.ipynb — full EDA, preprocessing, training, and evaluation

utils.py (optional) — helper functions if abstracted

⚙️ Installation & Usage
bash
Copy
Edit
# Clone the repo
git clone https://github.com/christylaminated/income-classification.git
cd income-classification

# (Optional) create a virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# Install requirements
pip install -r requirements.txt

# Open the notebook
jupyter notebook income-classification.ipynb
📚 Documentation
The entire process is documented step-by-step in the notebook

Inline comments explain major steps

Evaluation metrics and results are clearly displayed and discussed

🔄 Potential Next Steps
Try ensemble methods (Random Forest, Gradient Boosting)

Add feature selection or dimensionality reduction

Explore fairness across gender/ethnicity attributes

Tune hyperparameters using GridSearchCV

👤 Individual Contributions
This project was completed individually as part of Break Through Tech AI's Fall AI Studio program. All coding, analysis, and documentation were done by me.

