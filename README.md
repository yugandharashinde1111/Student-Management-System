# 🎓 Student Management System

A full-stack **Student Management System** built using **Spring Boot, Hibernate, JPA, Thymeleaf, and MySQL**.
This project provides separate dashboards for **teachers** and **students**, enabling seamless academic management.

---

## 🚀 Features

### 👩‍🏫 Teacher Dashboard

* Upload notes
* Update student attendance
* View student list

### 👩‍🎓 Student Dashboard

* View notes
* Submit assignments
* Check attendance

### 🔍 Other

* Search & organized UI

---

## 🛠 Tech Stack

* **Backend:** Spring Boot, Hibernate, JPA
* **Frontend:** Thymeleaf, HTML5, CSS3
* **Database:** MySQL
* **Tools:** Eclipse / IntelliJ IDEA, Git, GitHub

---

## ⚙️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yugandharashinde1111/Student-Management-System.git
   ```

2. **Create a MySQL database**

   ```sql
   CREATE DATABASE sms;
   ```

3. **Update `src/main/resources/application.properties`** with your MySQL credentials:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/sms
   spring.datasource.username=YOUR_DB_USERNAME
   spring.datasource.password=YOUR_DB_PASSWORD
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

4. **Run the project**

   ```bash
   mvn spring-boot:run
   ```

5. **Access in browser**

   ```
   http://localhost:8080/login
   ```

---
