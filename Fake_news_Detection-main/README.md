# 🚨 Fake News Detection

[![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  
[![GitHub stars](https://img.shields.io/github/stars/pavankumar0348/Fake_News_Detection)](https://github.com/pavankumar0348/Fake_News_Detection/stargazers)

---

## 📌 Project Summary  
Fake news spreads misinformation rapidly, creating confusion and affecting society.  
This project uses **Natural Language Processing (NLP)** and **Machine Learning (ML)** to classify news articles as **Real** or **Fake**.  
It supports a large dataset (~61K records) and includes a **Flask-based web interface** for real-time predictions.

---

## ✨ Key Features
✔ Detects fake news using multiple ML models  
✔ Achieved **87% accuracy** using Logistic Regression  
✔ Real-time prediction using Flask Web App  
✔ Professional dataset cleaning and preprocessing  
✔ Scalable and extendable for Deep Learning models

---

## 🧰 Tech Stack

| Category | Technologies |
|----------|-------------|
| Language | Python 3.9 |
| Libraries | scikit-learn, numpy, pandas, matplotlib, seaborn, NLTK, joblib |
| Deployment | Flask |
| Tools | GitHub, Jupyter Notebook |

---

## 📂 Dataset Overview  
Dataset includes:  
- `title`  
- `text`  
- `subject`  
- `news_url`  

### 🔹 Sample Dataset Preview
![](assets/dt1.PNG)  
![](assets/dt2.PNG)  
![](assets/dt3.PNG)  
![](assets/dt4.PNG)  
![](assets/dt5.PNG)

---

## 🧼 Data Preprocessing Steps
- Removed unnecessary columns  
- Handled missing values  
- Removed punctuation, symbols, numbers, and links  
- Tokenization, Lemmatization, Stopword removal  
- Text vectorized using **TF-IDF**

---

## 🧠 Machine Learning Models Used

| Model | Status |
|-------|--------|
| Logistic Regression | ⭐ Best Model |
| Random Forest | ✔ Tested |
| Gradient Boosting | ✔ Tested |
| XGBoost | ✔ Tested |
| Decision Tree | ✔ Evaluated |
| Multinomial Naive Bayes | ✔ Evaluated |
| Bernoulli NB | ✔ Evaluated |
| SGD Classifier | ✔ Evaluated |

---

### 📊 Model Performance
![](assets/Modelbulding.PNG)

**Best Result:** Logistic Regression — **~87% Accuracy**  
Model exported as `model.pkl` for deployment.

---

### ⚙ Model Workflow
![](assets/Modelbulding11.PNG)

---

## 🚀 Deployment (Flask App Workflow)

1. User enters news text on the webpage  
2. Text is preprocessed  
3. Model predicts **Real** or **Fake**  
4. Result shown instantly on screen  

### UI Preview  
![](assets/1.PNG)  
![](assets/2.PNG)

### Deployment Flow
![](assets/dep.PNG)

---

## 🛠 Installation & Usage

#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/pavankumar0348/Fake_News_Detection.git
cd Fake_News_Detection
```

#### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

#### 3️⃣ Run the Flask App
```bash
python app.py
```

#### 4️⃣ Open in Browser:
```
http://127.0.0.1:5000/
```

---

## 📌 Future Enhancements
- LSTM / BERT-based Deep Learning Model  
- Multi-language Fake News Detection  
- Cloud deployment (AWS / Heroku / Render)  

---

## 🏆 Author
👨‍💻 **Pavan Kumar M R**  
Fake News Detection using Machine Learning & NLP

---

## 📜 License
This project is licensed under the **MIT License**.

---
