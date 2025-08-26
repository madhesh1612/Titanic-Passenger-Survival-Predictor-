# 🛳️ Titanic Passenger Survival Predictor  

A deep learning project that predicts whether a Titanic passenger survived or not, based on their details.  
It also allows you to **search by passenger name** and check both the **predicted survival** and the **actual survival** from the dataset.  

---

## 📌 Features
- Preprocessing: text cleaning, tokenization, padding  
- CNN-based deep learning model for classification  
- Classification metrics (accuracy, loss, confusion matrix, classification report)  
- Graphical results visualization  
- **Interactive prompt mode**: type any passenger’s name and see survival prediction + actual outcome  

---

## 📂 Dataset
We used the **Titanic dataset** (`train.csv`) which contains details of passengers such as:  
- PassengerId  
- Name  
- Age  
- Sex  
- Pclass  
- Fare  
- Embarked  
- Survived (Target Variable: `1 = Survived, 0 = Did Not Survive`)  

---

## ⚙️ Installation
Clone this repository and install dependencies:  

```bash
git clone https://github.com/<your-username>/titanic-survival-predictor.git
cd titanic-survival-predictor
pip install -r requirements.txt
