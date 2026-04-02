#  NutriLens — Personalized Food Health Analyzer

##  Overview

NutriLens is a web-based application that analyzes packaged food ingredients and provides personalized health warnings and suggestions based on user conditions.

It simplifies complex food labels into easy, actionable insights.

---

##  Problem

* People struggle to understand food labels
* Harmful ingredients like sugar, oil, and sodium are hidden
* No personalized guidance based on health conditions

---

##  Solution

NutriLens converts ingredient lists into clear health decisions tailored to the user.

---

##  Features (V1)

* Select food items from a predefined list
* Choose health condition:

  * Diabetic
  * High Cholesterol
  * Weight Loss
* Rule-based ingredient analysis
* Personalized warnings and suggestions
* Simple and clean output

---

##  How It Works

User selects food + condition
↓
Ingredients fetched from database
↓
Analysis engine applies rules
↓
Warnings & suggestions generated
↓
Result displayed

---

##  Tech Stack

* **Backend:** Python (Flask)
* **Frontend:** HTML, CSS
* **Data:** Python Dictionary

---

##  Project Structure

food-analyzer/
│
├── app.py
├── data.py
├── logic.py
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   └── style.css

---

## ⚠️ Limitations

* Limited dataset
* Rule-based system (not AI yet)
* Not medical advice

---

##  Future Scope

* Image-based label scanning (OCR)
* AI-powered analysis
* Advanced personalization

---

##  Why This Project?

This project focuses on solving a real-world problem using simple but scalable backend logic.

---

##  Author

Alina — 1st semester student| Aspiring Developer

---

##  Status

 Version 1 in progress
