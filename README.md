                                                    Email Classification System

Description
This project classifies emails into:
- Spam 
- Promotion 
- Social 
- Important 

Technologies Used
- Python
- Pandas
- Scikit-learn
- NLTK

How to Run

1. Install libraries:
pip install pandas scikit-learn nltk joblib seaborn matplotlib

2. Train Model:
python train_model.py

3. Run Prediction:
python predict.py

Features
- Text preprocessing
- TF-IDF vectorization
- Logistic Regression model
- Real-time prediction
- Confidence score

Output Example

Input:
"Win a free gift now!!!"

Output:
Category: Spam
Confidence: 98%
