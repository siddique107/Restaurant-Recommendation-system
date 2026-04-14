🍽️ Smart Restaurant Recommendation System
A web-based restaurant recommendation system that suggests restaurants based on user preferences such as cuisine, budget, and ratings using Content-Based Filtering.

🚀 Features
🔍 Search restaurants by name
🍜 Filter by cuisine
💰 Budget-based filtering
⭐ Rating-based filtering
🤖 ML-based recommendations (TF-IDF + Cosine Similarity)
🎨 Modern UI (Dashboard Style)
⚠️ Error handling (No results / Not found)
🧠 How It Works
User enters:

Restaurant Name
Cuisine
Budget
Rating
System:

Finds the selected restaurant
Converts cuisine text into vectors (TF-IDF)
Calculates similarity using Cosine Similarity
Filters results:

Cuisine match
Budget
Rating
Displays top recommended restaurants

🛠️ Tech Stack
💻 Frontend
HTML
CSS
Font Awesome
⚙️ Backend
Python
Flask
📊 Data Processing
Pandas
NumPy
🤖 Machine Learning
Scikit-learn
TF-IDF Vectorizer
Cosine Similarity
📂 Project Structure
Restaurant-Recommendation-System/ │ ├── Flask/ │ ├── app1.py │ ├── restaurant1.csv │ ├── templates/ │ │ ├── index.html │ │ ├── recommend.html │ │ ├── result.html │ │ ├── error.html │ │ │ ├── static/ │ ├── screenshots/ │ ├── home.png │ ├── form.png │ ├── result.png │ │ └── README.md

📸 Screenshots
🏠 Home Page
Home Page
<img width="1902" height="911" alt="Screenshot 2026-04-14 101259" src="https://github.com/user-attachments/assets/111c7981-0096-4142-858a-be93b4578b7e" />
<img width="1898" height="1070" alt="Screenshot 2026-04-14 101326" src="https://github.com/user-attachments/assets/7829b7b1-7611-4b5b-9ed0-a0ed510cee9f" />

🔍 Recommendation Page
Form Page
<img width="1896" height="903" alt="Screenshot 2026-04-14 101454" src="https://github.com/user-attachments/assets/19d22320-9118-425b-9eeb-bde5f07d83bc" />

📊 Result Page
Result Page Result Page
<img width="1918" height="907" alt="Screenshot 2026-04-14 101517" src="https://github.com/user-attachments/assets/8155382f-e4ed-43e4-94b8-9099a6c55274" />
<img width="1894" height="905" alt="Screenshot 2026-04-14 101538" src="https://github.com/user-attachments/assets/33e8aa99-d77e-405d-89c5-9f42a9d46863" />

📊 Dataset
The dataset contains:

Restaurant Name
Rating
Mean Rating
Cuisines
Cost
Example:
Qaswa,4.3,4.1,north indian,800

📌 Conclusion
This project demonstrates how machine learning can be used to build a real-world recommendation system with a modern UI and filtering logic.

👨‍💻 Developed By
Siddique Sanadi
