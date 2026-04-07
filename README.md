# NutriLens — Personalized Food Health Analyzer

## Overview

NutriLens is a web-based application that analyzes packaged food ingredients and provides personalized health insights based on user conditions. It simplifies complex ingredient lists into clear, actionable decisions.

---

## Problem

* Food labels are difficult for most people to understand
* Harmful ingredients such as excess sugar, sodium, and additives often go unnoticed
* There is no simple system for personalized dietary guidance

---

## Solution

NutriLens uses a rule-based analysis system to evaluate ingredients and generate personalized health recommendations.

---

## How It Works

1. User selects a food item
2. Ingredient data is retrieved
3. The analysis engine processes the ingredients
4. Personalized suggestions are generated

---

## Features (Version 1)

* Predefined food dataset
* Health condition selection:

  * Diabetic
  * High Cholesterol
  * Weight Loss
* Ingredient-level analysis
* Clear and simple output

---

## Tech Stack

* Python
* Flask
* HTML
* CSS

---

## Architecture

User Input → Flask Route → Analysis Engine → Response

---

## Project Structure

```bash
NutriLens/
│── app.py
│── logic.py
│── data.py
│── templates/
│── static/
│── requirements.txt
│── README.md
```

---

## Run Locally
pip install -r requirements.txt
python app.py


---

## Screenshots

<img width="297" height="710" alt="image" src="https://github.com/user-attachments/assets/bd28cb41-4527-4eb3-a8de-7991d92fb70b" />
<img width="314" height="715" alt="image" src="https://github.com/user-attachments/assets/d5347b6c-82f7-4260-8e99-c2ab5b604b9f" />
<img width="610" height="299" alt="image" src="https://github.com/user-attachments/assets/c06c7c98-6fb8-43a6-adba-547355ab71aa" />
<img width="684" height="383" alt="image" src="https://github.com/user-attachments/assets/93306284-9de5-41e6-b7ba-d209974592c1" />


---

## Live Demo



---

## Future Improvements

* Real-time food search
* Database integration
* Improved UI/UX
* AI-based recommendations

---

## Version

V1: Rule-based ingredient analysis
V2 (Planned): AI-powered system

---

## Learning Goal

This project reflects my approach to learning backend by building real-world systems instead of only studying theory.
---

## Feedback

Open to suggestions and improvements.
