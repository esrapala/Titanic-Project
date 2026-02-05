🚢 Titanic Survival Prediction – Machine Learning Project
This project focuses on predicting passenger survival on the Titanic using classical machine learning algorithms.
It demonstrates a complete ML pipeline including data preprocessing, feature engineering, model comparison, and ensemble learning.
📌 Project Overview
The Titanic dataset is a well-known benchmark in machine learning.
In this project, multiple classification models are trained and evaluated, and an ensemble approach is used to improve performance.
Goal:
Predict whether a passenger survived (1) or not (0) based on demographic and travel-related features.
🧠 Models Used
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Decision Tree
Random Forest
Voting Classifier (Ensemble Model)
Cross-validation is used to compare model performances and select the most robust approach.
🛠️ Technologies & Libraries
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
📂 Project Structure
titanic_project/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── titanic_analysis.ipynb
│
├── readme.md
└── .gitignore
⚙️ How to Run
1️⃣ Clone the repository
git clone https://github.com/esrapala/Titanic-Project.git
cd Titanic-Project
2️⃣ Create and activate virtual environment
python -m venv venv
source venv/bin/activate   # macOS / Linux
3️⃣ Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn
4️⃣ Run the notebook
Open the Jupyter Notebook inside the notebooks/ folder and run all cells.
📊 Output
Model comparison using cross-validation
Visualization of feature distributions
Final predictions exported as titanic.csv
Ensemble model for improved accuracy
🎯 Key Learnings
Data cleaning and feature engineering
Comparing multiple ML classifiers
Cross-validation for model evaluation
Ensemble learning with Voting Classifier
End-to-end ML workflow
👩‍💻 Author
Esra Pala
Computer Engineering Student
Interested in Machine Learning & AI Applications
GitHub: https://github.com/esrapala
Linkedin: https://www.linkedin.com/in/esrapala/