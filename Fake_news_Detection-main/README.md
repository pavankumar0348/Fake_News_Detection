# 🚨 Fake News Detection

[![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  
[![GitHub stars](https://img.shields.io/github/stars/pavankumar0348/Fake_News_Detection)](https://github.com/pavankumar0348/Fake_News_Detection/stargazers)

---

## **Project Summary**
Fake news spreads misinformation rapidly, causing confusion and harm.  
This project leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** to detect whether a news article is **True** or **Fake**.  
It supports large datasets (~61,000+ records) and is deployed using **Flask** for easy web access.

---

## **Key Features**
- Detects fake news using multiple ML classifiers  
- Achieves **87%+ accuracy** with Logistic Regression  
- Web interface for live predictions  
- Clean and professional dataset preprocessing  
- Ready for future improvement using deep learning models  

---

## **Tech Stack**
- **Python 3.9**  
- Libraries: `scikit-learn`, `numpy`, `pandas`, `matplotlib`, `seaborn`, `NLTK`, `Joblib`, `Flask`  
- **Flask** for deployment  
- GitHub for version control  

---

## **Dataset Overview**
All datasets used are publicly available and contain columns like `title`, `text`, `subject`, `news_url`.  

### Sample Dataset Previews
![Dataset1](dt1.PNG)  
![Dataset2](dt2.PNG)  
![Dataset3](dt3.PNG)  
![Dataset4](dt4.PNG)  
![Dataset5](dt5.PNG)  

---

## **Data Preparation**
- Remove unwanted columns  
- Remove missing values  
- Clean text: remove punctuation, brackets, numbers, URLs  
- Prepare text for ML model input  

---

## **Machine Learning Workflow**
### Models Trained
- Logistic Regression ✅ (Best Performing)  
- Random Forest  
- Gradient Boosting Classifier (GBC)  
- XGBoost  
- Decision Tree  
- Multinomial Naive Bayes  
- Bernoulli Naive Bayes  
- Stochastic Gradient Descent  

### Model Accuracy
![Accuracy Score](accuracy_score.PNG)  

**Observation:** Logistic Regression gave the **highest accuracy** (~87%).  
Saved as `model.pkl` for deployment.

#### Model Building Flowchart
![Model Building](modelbuildingm.PNG)

---

## **Deployment**
The ML model is deployed using **Flask**:

1. Web interface collects text input from users.  
2. Input is sent to Flask backend.  
3. `model.pkl` predicts whether the news is True or Fake.  
4. Result is displayed instantly in the browser.

### Example Results
**Example 1**  
![Result1](1.PNG)  

**Example 2**  
![Result2](2.PNG)  

#### Deployment Flowchart
![Model Deployment](model_deployment.PNG)

---

## **Installation & Usage**
1. **Clone the repository**:

```bash
git clone https://github.com/pavankumar0348/Fake_News_Detection.git
