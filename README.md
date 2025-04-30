# Serendipity-aware-career-recommendation-system
🎓 Serendipity-Aware Career Recommendation System
This is a full-stack machine learning project that recommends suitable careers and bachelor courses to users based on their responses to a career test and an aptitude test. It incorporates serendipity-aware suggestions using TF-IDF vectorization, adding an element of exploration to traditional recommendation systems.

🚀 Features
🔐 User Authentication

User registration and login system with SQLite backend.

🧠 Career Test

A machine learning model (RandomForest) suggests a suitable career based on test responses.

🎲 Serendipity-Aware Recommendations

Generates up to 5 similar bachelor courses using TF-IDF vector similarity to the predicted career, enhancing discovery.

🧪 Aptitude Test (RIASEC-based)

Personality-type assessment using the Holland RIASEC model to suggest job roles fitting the user's traits.

📊 Recommendation Dashboard

View your main recommendation and all serendipitous career suggestions after completing tests.

🛠️ Tech Stack
Frontend: Streamlit

Backend: Python

Database: SQLite

Machine Learning: scikit-learn (RandomForest)

NLP: TF-IDF (for serendipity logic)

RIASEC Logic: Personality-based recommendation using predefined mappings

🧾 How It Works
User registers/logs in.

Takes the Career Test → ML model suggests a primary career.

Serendipity Module runs → TF-IDF fetches 5 similar careers from a bachelor courses dataset.

User takes Aptitude Test → Based on Holland Code (RIASEC) → Job role suggestions shown.

Recommendations Displayed → All results and alternatives shown on dashboard.
