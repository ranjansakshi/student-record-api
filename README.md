# STUDENT-RECORD-API
A simple Student Record Management System built with Node.js, Express, and MongoDB to manage student details via REST APIs. Supports creating, reading, updating, and deleting student records with validation and clean database structure. Ideal for learning backend and CRUD development.
# Student Record Management System

A simple and efficient **Student Record Management System** built using **Node.js**, **Express**, and **MongoDB**. This project performs full **CRUD operations** to manage student data including name, age, course, and city. Ideal for backend learning, academic projects, and beginner-level API development.

---

## 🚀 Features
- Add new student records
- View all students
- Update student information
- Delete student records
- MongoDB database integration
- RESTful API architecture
- Input validation & error handling

---

## 🛠 Tech Stack

| Technology | Purpose |
|----------|--------|
| Node.js | Backend runtime |
| Express.js | Web framework |
| MongoDB / Mongoose | Database & ORM |
| dotenv | Environment variables |
| CORS | Cross-origin access support |
STUDENT-RECORD/
├─ models/
│ └─ Student.js
├─ routes/
│ └─ studentRoutes.js
├─ controllers/
│ └─ studentController.js
├─ config/
│ └─ db.js
├─ server.js
└─ .env

Clone the repository

git clone https://github.com/Priyanshi006789/STUDENT-RECORD-API/edit/main/README.md cd STUDENT-RECORD

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone <your-repo-url>
cd student-record
2️⃣ Install Dependencies
npm install
3️⃣ Setup Environment Variables
Create a .env file in root:
MONGO_URI=your_mongodb_connection_string
PORT=5000

4️⃣ Start the Server
Development mode:
npm run dev

Production mode:
npm start


🔗 API Endpoints
MethodEndpointDescriptionGET/studentsGet all studentsPOST/studentsAdd a studentPUT/students/:idUpdate studentDELETE/students/:idRemove student
Sample Request
{
  "name": "Priyanshi",
  "course": "BCA",
  "age": 20,
  "city": "Delhi"
}


✅ Future Enhancements


UI frontend (React/Angular)


Authentication (JWT)


Search & filtering


Pagination


Dashboard UI



📝 License
This project is licensed for academic and learning use.

🙌 Author
Created by Priyanshi Agarwal

---

Would you like me to also generate?

📄 Project Report (Word/PDF)  
📊 Presentation PPT  
🗂 ER Diagram / Flowchart  
🎓 Abstract + Certificate page  

Just tell me!

---

## 📂 Project Structure
