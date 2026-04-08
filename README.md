# 🤖 QueryQuill – Intelligent College Query Chatbot

## 📌 Overview
QueryQuill is a Flask-based intelligent chatbot designed to automate and manage college-related queries. The system provides categorized responses using structured datasets and includes a secure hall booking module for institutional use.

The project aims to improve response efficiency, reduce manual workload, and provide a user-friendly interface for students and staff.

---

## ⚙️ Features

### 💬 Chatbot System
- Handles categorized queries such as admissions, courses, and general information  
- Retrieves responses from structured CSV datasets  
- Provides fast and accurate answers based on selected categories  

### 🏫 Hall Booking System
- Secure login authentication for authorized users  
- Real-time hall availability checking  
- Prevents duplicate bookings  
- Allows users to:
  - Book halls  
  - Update bookings  
  - Delete bookings  
  - View available halls  

---

## 🛠️ Tech Stack

- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Data Processing:** Pandas, NumPy  
- **Storage:** CSV-based structured datasets  

---

## 🔄 System Workflow

1. User selects a query category  
2. Chatbot retrieves relevant data from CSV  
3. Displays appropriate response  
4. For hall booking:
   - User logs in  
   - Selects date/time/hall  
   - System checks availability  
   - Booking is confirmed or rejected  

---

## 🎯 Key Highlights

- Integrated chatbot + booking system in a single application  
- Implemented validation to prevent duplicate bookings  
- Designed modular structure for scalability  
- Built responsive UI for better user experience  


## 🚀 Future Improvements

- Add NLP-based query understanding  
- Integrate database (SQL) instead of CSV  
- Deploy as a web application  
- Add multi-user authentication system  

---

## 📌 Conclusion
QueryQuill demonstrates how web development and data processing can be combined to build intelligent systems for real-world applications in educational institutions.
