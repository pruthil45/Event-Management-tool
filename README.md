# Infinity Vibes ♾️✨

**Infinity Vibes** is a full-stack web application developed during the **MSU Hackathon**.  
The project combines a Django backend, dynamic frontend assets, and a MySQL database to deliver an interactive, scalable, and hackathon-ready solution.

---

## 🚀 About the Project

Infinity Vibes is designed to manage events and media content while providing a smooth and engaging user experience.  
Built under strict hackathon time constraints, the project focuses on clean architecture, modularity, and rapid execution.

---

## ✨ Key Features

- Event-based modular architecture  
- Media and static asset handling  
- MySQL database integration  
- Scalable backend design  
- Clean and responsive frontend  
- Hackathon MVP-focused implementation  

---

## 🛠️ Tech Stack

- **Backend:** Python (Django)  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** MySQL  
- **Package Manager:** npm  
- **Tools:** Git, GitHub, VS Code  

---

## 📁 Project Directory Structure

INFINITY/
│── InfinityVibes/
│ ├── core/
│ │ ├── core/
│ │ ├── event/
│ │ ├── media/
│ │ ├── node_modules/
│ │ ├── static/
│ │ ├── manage.py
│ │ ├── package.json
│ │ ├── package-lock.json
│ │ └── temp.jpg
│
│── .gitignore


---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Infinity-Vibes.git
cd INFINITY/InfinityVibes
pip install django mysqlclient
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'infinity_vibes',
        'USER': 'root',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

🧠 Solution Approach

App-based Django structure

Separation of core logic and event management

Efficient handling of static and media files

Rapid MVP delivery with scalability in mind

🔮 Future Enhancements
User authentication and role management

Cloud database deployment

Improved UI/UX and responsiveness

Real-time notifications and updates

Mobile-first optimization
