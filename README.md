# 🍽️ Smart Restaurant Recommendation System

A web-based restaurant recommendation system that suggests restaurants based on user preferences such as cuisine, budget, and ratings using **Content-Based Filtering**.

---

## 🚀 Features

- 🔍 Search restaurants by name
- 🍜 Filter by cuisine
- 💰 Budget-based filtering
- ⭐ Rating-based filtering
- 🤖 ML-based recommendations (TF-IDF + Cosine Similarity)
- 🎨 Modern UI (Dashboard Style)
- ⚠️ Error handling (No results / Not found)

---

## 🧠 How It Works

1. User enters:
   - Restaurant Name
   - Cuisine
   - Budget
   - Rating

2. System:
   - Finds the selected restaurant
   - Converts cuisine text into vectors (TF-IDF)
   - Calculates similarity using Cosine Similarity

3. Filters results:
   - Cuisine match
   - Budget
   - Rating

4. Displays top recommended restaurants

---

## 🛠️ Tech Stack

### 💻 Frontend

- HTML
- CSS
- Font Awesome

### ⚙️ Backend

- Python
- Flask

### 📊 Data Processing

- Pandas
- NumPy

### 🤖 Machine Learning

- Scikit-learn
  - TF-IDF Vectorizer
  - Cosine Similarity

---

## 📂 Project Structure

Restaurant-Recommendation-System/
│
├── Flask/
│ ├── app1.py
│ ├── restaurant1.csv
│ ├── templates/
│ │ ├── index.html
│ │ ├── recommend.html
│ │ ├── result.html
│ │ ├── error.html
│ │
│ ├── static/
│
├── screenshots/
│ ├── home.png
│ ├── form.png
│ ├── result.png
│
│
└── README.md

---

## 📸 Screenshots

### 🏠 Home Page
<img width="1902" height="911" alt="Screenshot 2026-04-14 101259" src="https://github.com/user-attachments/assets/1507969e-d0c3-4a5f-a9bd-699aed1a1870" />
<img width="1898" height="1070" alt="Screenshot 2026-04-14 101326" src="https://github.com/user-attachments/assets/139f67a7-a404-4447-b2c1-c91d3635eeb0" />

### 🔍 Recommendation Page
<img width="1896" height="903" alt="Screenshot 2026-04-14 101454" src="https://github.com/user-attachments/assets/6f18ca58-2738-486c-a7c4-4ce2be188bfa" />

### 📊 Result Page
<img width="1918" height="907" alt="Screenshot 2026-04-14 101517" src="https://github.com/user-attachments/assets/286504ed-5e3d-4793-b855-93bd3fac3066" />
<img width="1894" height="905" alt="Screenshot 2026-04-14 101538" src="https://github.com/user-attachments/assets/6711e8e8-5d06-471b-a352-0fb6c33097af" />
---

## 📊 Dataset

The dataset contains:

- Restaurant Name
- Rating
- Mean Rating
- Cuisines
- Cost

### Example:

Qaswa,4.3,4.1,north indian,800

---

## 📌 Conclusion

This project demonstrates how machine learning can be used to build a real-world recommendation system with a modern UI and filtering logic.

---

## 👨‍💻 Developed By

**Siddique Sanadi**
