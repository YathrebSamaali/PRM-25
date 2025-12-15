# PRM-25

## 📝 Project Description
PRM-25 is a **full-stack web application** for managing properties.  
It provides a **secure, scalable, and user-friendly system** to handle property data, users, and transactions efficiently.

- **Frontend:** Built with Angular for a responsive and interactive UI.  
- **Backend:** Spring Boot with Java for robust APIs and data management.  
- **Database:** MySQL for storing property, user, and transaction data.

This project is designed for both academic demonstration and practical use in property management systems.

---

## ✨ Features
- 🔐 Authentication and authorization (login, roles)  
- 🏠 Property management (add, update, delete, list properties)  
- 👥 User management (admins, clients)  
- 📊 Dashboard and analytics for property tracking  
- ⚡ Integration of backend APIs with frontend Angular app  

---

## 🛠️ Technologies Used
- **Frontend:** Angular, HTML5, CSS3, Bootstrap  
- **Backend:** Spring Boot, Java 17, RESTful APIs  
- **Database:** MySQL  
- **Tools:** Postman, Git, GitHub  

---

## 🚀 How to Run
### Backend (Spring Boot)
````bash
cd backend
./mvnw clean install   # install dependencies
./mvnw spring-boot:run # start backend server
````

API available at: http://localhost:8080

### Frontend (Angular)
````bash
cd frontend
npm install    # install dependencies
ng serve       # start frontend server
````
Open in browser: http://localhost:4200
Frontend communicates with backend automatically.
