Email Spam Detection using Machine Learning & Deep Learning
Semester Project – Riphah International University
Name : Abdul Wahid Modassar
SAP ID : 65292
Course : Artificial intelligence
📌 Project Summary

This project implements an Email Spam Detection system using Machine Learning and Deep Learning techniques.
The model identifies whether an email is Spam or Ham (Not Spam) based on its text content.

Two algorithms are used:

Linear Regression (as a classifier)

Deep Neural Network (DNN) trained on epochs

The dataset is taken from Kaggle (spam.csv).
Text preprocessing, TF-IDF vectorization, model training, evaluation, and predictions are all included.

This project is part of the course: Artificial Intelligence 3 (AI-3).

⚙️ Installation Steps
1. Clone the Repository
git clone https://github.com/yourusername/email-spam-detection.git
cd email-spam-detection

2. Install Dependencies
pip install -r requirements.txt


If you do not have a requirements file, install manually:

pip install pandas numpy scikit-learn matplotlib seaborn tensorflow joblib

3. Add Dataset

Place the file spam.csv in the project folder.

Dataset link (Kaggle):
Search “SMS Spam Collection Dataset – Kaggle”

4. Run the Program
python spam_detection.py

📦 Dependencies
Library	Purpose
pandas	Load and clean dataset
numpy	Mathematical operations
scikit-learn	ML model, TF-IDF, metrics
tensorflow/keras	Deep learning model
matplotlib & seaborn	Graphs (confusion matrix, accuracy, loss)
joblib	Save models

Install all dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn tensorflow joblib

▶️ Example Usage
Train the Models
python spam_detection.py

Predict a Custom Email

Inside Python:

predict_email("Congratulations! You have won a free prize. Click the link now.")


Output:

"SPAM"


Another example:

predict_email("Dear sir, your meeting is scheduled for tomorrow.")


Output:

"HAM"

👨‍🎓 Author Details
Field	Information
Name:	Abdul Wahid Modassar
SAP ID:	65292
Course:	Artificial Intelligence 3 (AI-3)
University:	Riphah International University
📁 Project Contents
Email-Spam-Detection/
│── README.md
│── spam_detection.py
│── spam.csv
│── model_lr.pkl
│── model_dnn.h5
│── vectorizer.pkl
│── confusion_matrix.png
│── accuracy_graph.png
│── loss_graph.png
│── project_report.pdf
│── documentation.pdf

📽 Video Demonstration

(Upload to YouTube and paste your link here)

YouTube Link: <Your Video URL>

🎯 Final Notes

This project fulfills all official requirements:

✔ Python Implementation
✔ PDF Report
✔ Documentation
✔ Confusion Matrix Graph
✔ Training on Epochs
✔ README.md
✔ Video Demonstration
✔ GitHub Repository