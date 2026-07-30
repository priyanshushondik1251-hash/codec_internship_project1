# 📧 Spam Email Detection using Machine Learning

A machine learning project that classifies emails as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and multiple classification algorithms.

---

## 📌 Project Overview

Spam emails are one of the biggest challenges in digital communication. This project builds an end-to-end spam email detection system by applying text preprocessing, feature extraction, and machine learning models to classify emails accurately.

The workflow includes:

- Data loading
- Exploratory Data Analysis (EDA)
- Text preprocessing
- TF-IDF feature extraction
- Model training
- Model comparison
- Hyperparameter tuning
- Testing on new email samples

---

## 📂 Dataset

The project uses the **Spam Email Dataset** from Kaggle.

**Features**

- `text` → Email content
- `spam`
  - `1` = Spam
  - `0` = Ham (Not Spam)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset shape and information
- Missing value check
- Duplicate value removal
- Spam vs Ham distribution
- Email length distribution
- Most common words in Spam emails
- Most common words in Ham emails

---

## 🧹 Text Preprocessing

Before training the models, the email text was cleaned using:

- Convert text to lowercase
- Remove URLs
- Remove numbers
- Remove punctuation
- Remove stopwords
- Lemmatization

This improves the quality of the text data and helps the model learn meaningful patterns.

---

## 🔤 Feature Engineering

The processed text is converted into numerical features using:

- **TF-IDF Vectorizer (Term Frequency–Inverse Document Frequency)**

---

## 🤖 Machine Learning Models

The following models were trained and compared:

- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Machine (Linear SVM)

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

---

## 🚀 Model Improvement

To improve the performance of the best model:

- ✅ 5-Fold Cross Validation
- ✅ GridSearchCV Hyperparameter Tuning

Hyperparameters tuned include:

- TF-IDF maximum document frequency
- N-gram range
- Linear SVM regularization parameter (`C`)

---

## 🧪 Sample Predictions

Example predictions:

| Email | Prediction |
|-------|------------|
| Congratulations! You've won a free iPhone! | Spam |
| Please find the project report attached. | Ham |
| Verify your account immediately. | Spam |
| Meeting tomorrow at 10 AM. | Ham |

---

## 📁 Project Structure

```
Spam-Email-Detection/
│
├── spam_email_detection.ipynb
├── emails.csv
├── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/spam-email-detection.git
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
```

### 3. Download NLTK resources

```python
import nltk
nltk.download("stopwords")
nltk.download("wordnet")
```

### 4. Run the notebook

Open:

```
spam_email_detection.ipynb
```

using Jupyter Notebook or Google Colab.

---

## 📈 Future Improvements

- Deploy using Streamlit or Flask
- Build a web interface
- Try Deep Learning models (LSTM/BERT)
- Add email attachment analysis
- Real-time spam detection API

---

## 📚 Learning Outcomes

Through this project, I learned:

- Natural Language Processing (NLP)
- Text preprocessing techniques
- TF-IDF feature extraction
- Machine Learning pipelines
- Model evaluation metrics
- Cross-validation
- Hyperparameter tuning using GridSearchCV

---

## 👨‍💻 Author

**Priyanshu Kumar**

B.Tech Computer Science Engineering  
Interested in Machine Learning, AI, and Data Science.

---

## ⭐ If you found this project useful

Give this repository a ⭐ to support the project!