# SMS-SPAM-DETECTION
# overview 
Spam messages are one of the most common cybersecurity threats, often used for phishing, scams, and spreading malicious links. Detecting spam automatically helps protect users from fraud and improves communication safety. This project applies machine learning to classify SMS messages as either spam or ham (not spam).
The goal of this project is to build a lightweight AI model that can:
- Analyze SMS text content.
- Identify whether the message is spam or legitimate.
- Provide accurate classification with minimal computational cost.
# Process
- Dataset
- SMS Spam Collection dataset
- Preprocessing
- Text cleaning and normalization.
- Feature extraction using TF‑IDF vectorization.
- Model
- Naive Bayes classifier (MultinomialNB) chosen for its efficiency in text classification tasks.
- Training & Evaluation
- Train/test split (80/20).
- Evaluate using accuracy, precision, recall,
- This project demonstrates how AI/ML techniques can be applied to real‑world cybersecurity problems. The model is simple, fast, and effective, making it suitable for integration into larger spam‑filtering systems.

# features 
-  Spam vs Ham Classification – Detects whether an SMS message is spam or legitimate.
- Text Preprocessing – Cleans and converts raw SMS text into numerical features using TF‑IDF.
- Lightweight Model – Uses Naive Bayes for fast training and prediction.
- High Accuracy – Achieves ~95% accuracy on test data.
- Evaluation Metrics – Provides accuracy, precision, recall, and confusion matrix.
- Custom Prediction – Allows you to test your own SMS messages for spam detection.

# Technologies Used
- Python 3.x – Programming language.
- scikit‑learn – Machine learning library (Naive Bayes, TF‑IDF vectorizer).
- pandas & numpy – Data handling and preprocessing.
- matplotlib – Visualization (optional for confusion matrix heatmap).

# Steps to Install and Run
-  Clone the repository or Download project
   git clone https://github.com/yourusername/spam-sms-detection.git
cd spam-sms-detection
- Install Dependencies
- pip install pandas scikit-learn matplotlib
-  Add Dataset
- Download the SMS Spam Collection dataset.
- Save it as spam.csv in the project folder.
   - Run the Project
python spam_sms.py
# instructions for testing 
- dataset check
- Run:
print(data.head())
print(data['label'].value_counts())
- Confirms SMS messages are loaded with ham and spam.
- Train/Test Split
print(len(X_train), len(X_test))
-  About 80% training, 20% testing.
- Model Evaluation
Run spam_sms.py → prints accuracy (~95%), classification report, and confusion matrix.
- Custom SMS Test
 # Future inhancements 
- Deploy as a web app for real‑time SMS filtering.
- Extend to email spam detection.
- Experiment with deep learning models (LSTM, Transformers) for improved accuracy.
  # screenshots
  <img width="1920" height="1080" alt="Screenshot 2025-11-24 153420" src="https://github.com/user-attachments/assets/a00dba93-e52c-45dd-a71c-fd4e28b41762" />
<img width="1919" height="1079" alt="Screenshot 2025-11-24 153353" src="https://github.com/user-attachments/assets/6d1e0e11-38ca-43ec-b624-cc660b81eb7a" />

# AUTHOR 
- Aditi Sharma ( 25BCY10070)
- BTECH.CSE COMPUTER SCIENCE AND ENGINEERING (CYBER SECURITY AND DIGITAL FORENSICS) 
- VIT BHOPAL 


