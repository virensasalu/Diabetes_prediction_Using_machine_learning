# End-to-End Diabetes Prediction Application using Machine Learning (Mini Project)  

## Table of Contents
- [Overview](#overview)  
- [Motivation](#motivation)  
- [Demo](#demo)  
- [Learning-Objectives](#learning-objectives)  
- [Technical-Details](#technical-details)  
- [Technologies-Used](#technologies-used)  
- [Installation](#installation)  
- [Run](#run)  
- [Bug--Feature-Requests](#bug--feature-requests)  
- [Credits](#credits)  
- [Note](#note)  

---

## Overview  
This project predicts whether a person has **diabetes** based on key health indicators such as:  
- Number of pregnancies  
- Insulin level  
- Age  
- BMI  

The dataset, sourced from [Kaggle](https://www.kaggle.com/), originates from the **National Institute of Diabetes and Digestive and Kidney Diseases**.  
All patients are **female**, aged **21+ years**, and of **Pima Indian heritage**.  
The model is implemented using a **Random Forest Classifier**.  

---

## Motivation  
The aim was to build a **complete, end-to-end machine learning application** — from data preprocessing to deployment — while gaining hands-on experience with deployment platforms like [Heroku](https://www.heroku.com/).  

With diabetes cases increasing globally due to sedentary lifestyles, early detection can prevent severe health complications.  
This project uses machine learning to **assist in early diagnosis** and showcase how technology can help in healthcare.  

On a personal note, this was both a **learning experience** and an opportunity to create something socially beneficial.  

---

## Demo  
[Live Application on Heroku](https://mldiabete.herokuapp.com/)  

---

## Learning Objectives  
The main goal was to create an **end-to-end ML project**.  

Tasks included:  
- Data gathering  
- Exploratory Data Analysis (EDA)  
- Data visualization  
- Data preprocessing & feature engineering  
- Model training & evaluation  
- Model deployment using Flask on Heroku  

---

## Technical Details  
- **Model Training**: Implemented using `scikit-learn`’s Random Forest Classifier.  
- **Web Framework**: Flask for the front-end and back-end integration.  
- **Deployment**: Hosted on Heroku with proper environment configuration.  
- **Workflow**:  
  1. User inputs health data (pregnancies, insulin, BMI, age, etc.)  
  2. Data is preprocessed and fed to the trained model.  
  3. Prediction (Positive / Negative for diabetes) is displayed.  
- **Scalability**: Can handle moderate concurrency; scalable via Heroku dynos or Docker-based deployment.  

---

## Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg)  

- **Python 3.7+**  
- **scikit-learn** – Machine learning model  
- **Flask** – Web application framework  
- **Heroku** – Cloud deployment  
- **NumPy, Pandas** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  

---

## Installation  
1. **Clone the repository**  
   ```bash
   git clone 

   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt

   ```
## Run

Once the app is running, open your browser and go to:
```bash
http://127.0.0.1:5000/
```
Enter the required details in the form, and the model will display the prediction result.

## Bug / Feature Requests

**Found an issue or have an idea?**
	•	Report a bug → GitHub Issues
	•	Request a feature → New Request

## Credits
	•	Inspiration Krish Naik – Popular Data Science educator (YouTube Channel)
	•	Icons: Icons8