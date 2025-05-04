Decision Tree Classifier - Bank Marketing Dataset (Intern Task 3)

This repository contains my solution for Intern Task 3 as part of the Prodigy Infotech Internship. The goal is to use a Decision Tree Classifier to predict whether a client will subscribe to a term deposit.

Dataset

Bank Marketing Dataset from the UCI Machine Learning Repository  
Used file: bank-full.csv (semicolon-separated)  
Target variable: y (yes/no)

Link: https://archive.ics.uci.edu/ml/datasets/bank+marketing

Task Summary

- Loaded and preprocessed the dataset
- Encoded categorical variables using LabelEncoder
- Split data into training and test sets (70/30)
- Trained a Decision Tree Classifier (criterion='entropy', max_depth=5)
- Evaluated with accuracy, confusion matrix, and classification report
- Visualized the decision tree

Results

- Accuracy: ~89.5%
- Confusion Matrix:
  [[11596   370]
   [ 1053   545]]
- Class 0 F1-score: 0.94
- Class 1 F1-score: 0.43

Technologies Used

- Python
- pandas, scikit-learn, matplotlib

How to Run

1. Clone the repository:
   git clone https://github.com/yourusername/intern-task-3.git
   cd intern-task-3

2. Download bank-full.csv from the UCI repository:
   https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank.zip

3. Open Intern_task_3.ipynb in Jupyter or Google Colab and run all cells.

License

This project is licensed under the MIT License.

Contact

For questions, feel free to reach out via email or LinkedIn.
