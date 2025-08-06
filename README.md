# projects-api
# 🚂 Coal Transfer Management System

A Java Spring Boot-based backend application designed to track and manage the transfer of coal between source and destination points. This system supports inventory updates, train scheduling, and real-time status tracking.

---

## ⚙️ Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- REST APIs
- Postman (for API testing)
- Git

---

## 📌 Features

- 📦 **Coal Inventory Management**  
  Tracks available coal stock at warehouses/terminals.

- 🚆 **Train Scheduling & Dispatch**  
  Plans train movements for coal transportation between locations.

- 📡 **Live Train Tracking (Optional)**  
  Fetches real-time status and estimated arrival times.

- 🔄 **Loading & Unloading Logs**  
  Records coal load/unload operations with timestamps.

- 🧾 **Audit and Logs**  
  Maintains logs for each transaction (optional).

---

## 🗃️ Database Tables

- `warehouses` – stores location and stock data  
- `trains` – holds train IDs and schedules  
- `movements` – records coal transfer events  
- `users` – for admin/operator roles (if implemented)

---

## 🚀 How to Run

1. Clone the repository
2. Set up MySQL DB and configure `application.properties`
3. Run `EmployeeManagementApplication.java` or main app class
4. Use Postman to test endpoints like:
   - `GET /trains`
   - `POST /transfer`
   - `GET /inventory`

---

## 📂 Future Enhancements

- JWT-based user authentication
- Real-time GPS tracking integration
- Admin dashboard (React or Angular frontend)

---

## 🧑‍💻 Developed By

**Avula Guru Prasad**  
[LinkedIn](https://www.linkedin.com/in/guruprasad-avula-150440246)

