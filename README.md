# University Event Management System

A desktop-based Event Management System built with Python CustomTkinter and MySQL to manage university events, users, registrations, and feedback through an easy graphical interface.

---

## 🚀 Features

- Add, update, delete and view events  
- Manage users (add/update/delete)  
- Register users for events  
- Feedback system with ratings  
- Dashboard with statistics  
- Search & sort events  
- Top rated events graph  

---

## 🛠 Technologies Used

- Python  
- CustomTkinter (GUI)  
- MySQL Database  
- Matplotlib (Charts)  
- Pillow (Images)

---

## 📂 Project Structure

```
UniversityEventsManagement/
│
├── main.py
├── db.py
├── dashboard.py
├── events.py
├── users.py
├── feedback.py
├── assets/
│   └── logo.jpg
└── README.md
```

---

## ⚙ How to Run the Project

### 1. Install Required Libraries

Run this command in terminal:

```
pip install customtkinter mysql-connector-python matplotlib pillow
```

---

### 2. Setup MySQL Database

Open MySQL Workbench and run:

```
CREATE DATABASE university_events;
USE university_events;
```

Create tables using provided SQL script:

- users  
- events  
- registrations  
- feedback  

---

### 3. Configure Database Connection

Open **db.py** and set your own MySQL details:

```python
conn = mysql.connector.connect(
    host="localhost",
    user="root",
    password="YOUR_PASSWORD",
    database="university_events"
)
```

📝 Note:  
- Host usually remains → localhost  
- Username → your MySQL user  
- Password → your own password  

---

### 4. Run the Application

In project folder:

```
python main.py
```

---

## 📌 System Workflow

1. Admin adds events  
2. Admin adds users  
3. Users register to events  
4. Feedback is submitted  
5. Dashboard shows analytics  

---

## ❗ Common Issues

- **Access Denied** → Check password in db.py  
- **Database not found** → Create DB first  
- **Tables missing** → Run SQL script again  
- **Connection error** → Start MySQL server  

---

## 🔮 Future Improvements

- Login system  
- Student panel  
- Email notifications  
- Role-based access  

---

## 👨‍💻 Developed By

Abdul Samad
Faisal Haroon 
Muhammad Talha
M Usman
Tooba Zahid
