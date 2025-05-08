# amazon_producr_review
# 📝 Sentiment Detection for Amazon Product Reviews

This Django-based web application performs **sentiment analysis** on Amazon product reviews using Natural Language Processing (NLP). It supports two types of users: **Admin** and **User**. The admin can manage user access and monitor classification results, while users can view sentiment data, classification outcomes, and the review dataset.

---

## 🔧 Tech Stack

- **Backend:** Python, Django  
- **Frontend:** HTML, CSS, Bootstrap (optional)  
- **Database:** SQLite / MySQL (based on your settings)  
- **Machine Learning:** scikit-learn, pandas, NLTK  

---

## 👥 User Roles

### 🛠️ Admin
- Login securely.
- View list of registered users.
- Activate/deactivate user accounts.
- View sentiment classification results.

### 🙋 User
- Register on the platform.
- Wait for activation by the admin.
- Login after activation.
- Access the following:
  - Sentiment-classified Amazon product reviews.
  - Detailed classification results.
  - Original dataset used for training/testing.

---

## 📂 Project Structure (Sample)
# 📝 Sentiment Detection for Amazon Product Reviews

This Django-based web application performs **sentiment analysis** on Amazon product reviews using Natural Language Processing (NLP). It supports two types of users: **Admin** and **User**. The admin can manage user access and monitor classification results, while users can view sentiment data, classification outcomes, and the review dataset.

---

## 🔧 Tech Stack

- **Backend:** Python, Django  
- **Frontend:** HTML, CSS, Bootstrap (optional)  
- **Database:** SQLite / MySQL (based on your settings)  
- **Machine Learning:** scikit-learn, pandas, NLTK  

---

## 👥 User Roles

### 🛠️ Admin
- Login securely.
- View list of registered users.
- Activate/deactivate user accounts.
- View sentiment classification results.

### 🙋 User
- Register on the platform.
- Wait for activation by the admin.
- Login after activation.
- Access the following:
  - Sentiment-classified Amazon product reviews.
  - Detailed classification results.
  - Original dataset used for training/testing.

---

## 📂 Project Structure (Sample)
sentiment_analysis_project/
├── sentiment_app/
│ ├── migrations/
│ ├── templates/
│ │ ├── admin/
│ │ ├── user/
│ ├── static/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── forms.py
├── sentiment_model/
│ └── model.pkl
├── dataset/
│ └── amazon_reviews.csv
├── sentiment_analysis_project/
│ └── settings.py
├── manage.py
└── README.md


---

## 🚀 How to Run

 1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/sentiment-amazon-django.git
   cd sentiment-amazon-django

 2.  python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activae

 3. pip install -r requirements.txt

 4. python manage.py makemigrations
python manage.py migrate

 5. python manage.py runserver

6.Visit: http://127.0.0.1:8000/

Login as admin to activate users

Users can register and login after activation








