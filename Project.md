# Event Registration Portal

A web-based Event Registration Portal developed using HTML, Java, and MySQL. The system allows users to register for events online and enables administrators to manage events and participants efficiently.

---

## 📌 Project Description

The Event Registration Portal is designed to automate the event registration process. Users can browse available events, register online, and view their registration details. Administrators can create, update, and manage events and participant records.

---

## 🎯 Objectives

- Simplify event registration and management.
- Reduce manual paperwork.
- Store participant information securely.
- Provide a user-friendly interface.
- Improve event organization efficiency.

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Servlet & JSP

### Database
- MySQL

### Server
- Apache Tomcat

---

## 📂 Project Structure

Event-Registration-Portal/
│
├── src/
│ ├── controller/
│ ├── model/
│ ├── dao/
│ └── util/
│
├── WebContent/
│ ├── index.html
│ ├── login.jsp
│ ├── register.jsp
│ ├── events.jsp
│ ├── admin.jsp
│ └── css/
│
├── database/
│ └── event_registration.sql
│
└── README.md

---

## ✨ Features

### User Features
- User Registration
- User Login
- View Events
- Register for Events
- View Registration Details
- Update Profile

### Admin Features
- Admin Login
- Add Events
- Edit Events
- Delete Events
- View Participants
- Manage Registrations

---

## 🗄️ Database Design

### Users Table

| Column | Type |
|----------|----------|
| user_id | INT |
| name | VARCHAR(100) |
| email | VARCHAR(100) |
| password | VARCHAR(255) |
| phone | VARCHAR(15) |

### Events Table

| Column | Type |
|----------|----------|
| event_id | INT |
| event_name | VARCHAR(100) |
| description | TEXT |
| event_date | DATE |
| venue | VARCHAR(100) |

### Registrations Table

| Column | Type |
|----------|----------|
| registration_id | INT |
| user_id | INT |
| event_id | INT |
| registration_date | DATE |

---

## 🔗 Entity Relationship

Users (1) ---- (M) Registrations (M) ---- (1) Events

---

## 👤 Use Cases

### User
- Sign Up
- Login
- View Events
- Register for Event
- View Registration Status

### Admin
- Login
- Add Event
- Update Event
- Delete Event
- Manage Participants

---

## ⚙️ Installation

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/event-registration-portal.git
```

### Step 2: Create Database

```sql
CREATE DATABASE event_registration;
```

### Step 3: Configure MySQL Connection

Update database username and password in your Java configuration file.

### Step 4: Deploy Application

- Import project into Eclipse/IntelliJ IDEA
- Configure Apache Tomcat
- Run the project

---

## 🚀 Future Enhancements

- Online Payment Gateway
- Email Notifications
- QR Code Event Pass
- Attendance Tracking
- Mobile Application
- Analytics Dashboard

---

## 📖 Conclusion

The Event Registration Portal provides a simple, secure, and efficient solution for managing event registrations. It reduces manual effort, improves accuracy, and enhances the overall experience for both participants and event organizers.

---
