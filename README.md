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
<img width="1902" height="911" alt="Screenshot 2026-04-14 101259" src="https://github.com/user-attachments/assets/8c1c7c3e-b7b9-4e4b-9c09-729b7f691adb" />
<img width="1898" height="1070" alt="Screenshot 2026-04-14 101326" src="https://github.com/user-attachments/assets/16802966-fe82-46a7-90b3-6ae56c5feaf7" />
### 🔍 Recommendation Page

<img width="1896" height="903" alt="Screenshot 2026-04-14 101454" src="https://github.com/user-attachments/assets/e703c7c0-e95c-45ce-8d58-bcafc1ac8a59" />
### 📊 Result Page
<img width="1918" height="907" alt="Screenshot 2026-04-14 101517" src="https://github.com/user-attachments/assets/870bc27e-fdf0-4280-b4f7-7e598612d4f8" />
<img width="1894" height="905" alt="Screenshot 2026-04-14 101538" src="https://github.com/user-attachments/assets/8877f93e-634e-4d22-9f2c-de8567c902ab" />

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
