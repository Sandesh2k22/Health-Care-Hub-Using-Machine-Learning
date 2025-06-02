🩺 Medical Recommendation System This is a web-based healthcare platform that uses a machine learning model to predict diseases based on user-input symptoms. It then provides the user with the predicted disease description, precautions, medications, recommended diet, and workout routines. 📁 Features • Predicts disease from symptoms using an SVC model. • Provides: o Disease Description o Precautions o Medications o Diet Recommendations o Workouts • User-friendly web interface built with Flask. • Additional Pages: About, Contact, Developer Info, Blog, Google Map Integration, and a Healthcare Bot. 🛠️ Tech Stack • Backend: Python, Flask • Frontend: HTML, CSS, JS (via Jinja2 templates) • Model: Scikit-learn (SVC model) • Data: CSV datasets for symptoms, precautions, medications, diets, etc.

 How to Run This Project

Clone the Repository or open project file given in CD  git clone Deveshtayade/Health_Care_Hub_using_ML

Create a Virtual Environment (Recommended)  python -m venv venv # On Windows  venv\Scripts\activate # On macOS/Linux  source venv/bin/activate

Install Required Libraries  pip install -r requirements.txt ( If you don't have requirements.txt, install manually ) :  pip install flask pandas numpy scikit-learn

Ensure Directory Structure

▶️ Run the Application  python app.py ( Navigate to http://127.0.0.1:5000/ in your browser to use the app. )

📝 Project Structure • app.py: Main Flask application. • models/svc.pkl: Pre-trained disease prediction model. • datasets/: CSV files with medical data. • templates/: HTML templates for the website. • static/: (Optional) For CSS/JS files if used. 📌 Notes • Ensure your symptom input is comma-separated like: • headache,fatigue,cough • Avoid typos or invalid symptom names.
