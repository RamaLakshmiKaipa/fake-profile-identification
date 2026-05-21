# Fake Profile Identification in Social Networks

> Detecting fake social media profiles using Machine Learning and NLP techniques.

---

## 🔍 About the Project

This project identifies fake profiles on social networks by analyzing user metadata, text features, and behavioral patterns. It uses a combination of **SVM** and **KNN** classifiers through a **Voting Classifier** ensemble to improve prediction accuracy.

Built with **Django** as the web framework and **Python** for machine learning — allowing users to input profile details and get real-time predictions.

---

## 🎯 Key Results

- ✅ **92% Accuracy** achieved using ensemble ML model (SVM + KNN)
- ✅ Processed **50,000+ social media profiles**
- ✅ Reduced feature processing time by **30%** through optimized multithreading
- ✅ Improved precision over baseline models

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Backend | Python, Django |
| Machine Learning | scikit-learn, SVM, KNN, VotingClassifier |
| NLP & Data | Pandas, NumPy, CountVectorizer |
| Visualization | Matplotlib, Seaborn |
| Database | MySQL |
| Frontend | HTML, CSS |

---

## 📁 Project Structure

```
fake-profile-identification/
│
├── Remote_User/          # User registration, login, profile prediction
├── Service_Provider/     # Admin/service provider views
├── Template/             # HTML templates and static files
├── Database/             # SQL schema
├── Profile_Datasets.csv  # Training dataset
└── manage.py             # Django entry point
```

---

## ⚙️ How It Works

1. User enters social media profile details
2. System preprocesses and cleans text data using NLP
3. ML model (SVM + KNN Voting Classifier) predicts — **Fake** or **Genuine**
4. Result is displayed to the user in real time

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/RamaLakshmiKaipa/fake-profile-identification.git

# 2. Install dependencies
pip install django pandas numpy scikit-learn matplotlib seaborn openpyxl

# 3. Run database migrations
python manage.py migrate

# 4. Start the server
python manage.py runserver

# 5. Open browser
http://127.0.0.1:8000/
```

---

## 👩‍💻 Author

**K. Rama Lakshmi**  
MCA Graduate | Java Developer | ML Enthusiast  
📧 ramalakshmikaipa12@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/kaipa-rama-lakshmi)
