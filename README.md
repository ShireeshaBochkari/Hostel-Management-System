# Hostel Management System

A robust, full-stack web application designed to digitalise and automate daily hostel administration. Built with a secure **Java Spring Boot REST API** backend and an interactive **Vanilla JavaScript** frontend, this system facilitates seamless role-based workflows for administrators ("Owners") and residents ("Students").

## ✨ Key Features

* **Role-Based Dashboards:** Distinct portal experiences for Hostellers/Students and Hostel Owners/Managers.
* **Authentication & Security:** Secure user login and registration powered by **JWT (JSON Web Tokens)**.
* **Room Management:** Dynamic room creation, configuration (amenities, capacity), and automated allocation tracking.
* **Payment Tracking:** Digital logging and tracking of rent dues and transaction history.
* **Grievance Redressal:** A complaint system allowing students to report issues and admins to update resolution statuses.
* **Visitor Logging:** Tracking system for managing outsider entries, logs, and approval statuses.
* **Notice Board & Messaging:** Real-time information broadcast system for announcements and direct updates.

## 🛠️ Tech Stack

### Backend
* **Framework:** Java Spring Boot
* **Security:** Spring Security & JWT 
* **Build Tool:** Maven (`pom.xml` configured)
* **Data Access:** Spring Data JPA / Hibernate

### Frontend
* **Core:** HTML5, CSS3, Modern JavaScript (ES6+)
* **Styling:** Custom CSS layout engine 
* **API Client:** Fetch API with dynamic routing configurations (`config.js`, `app.js`)

## 📂 Project Architecture

```text
hostel-management/
├── backend/                   # Spring Boot REST API
│   ├── src/main/java/...      # Config, Controllers, Entities, DTOs, Services
│   ├── pom.xml                # Maven Dependencies
│   └── Dockerfile             # Containerisation setup
├── frontend/                  # Responsive Web Client
│   ├── css/style.css          # Global and dashboard styling
│   ├── js/                    # Dashboards, Config, and Auth logic
│   └── *.html                 # Clean, semantic structure templates
└── DEPLOYMENT_GUIDE.md        # Detailed setup and environment guide
```

## 🚀 Getting Started

1. **Prerequisites:** Ensure you have JDK 17+, Maven, and a relational database (e.g., MySQL/PostgreSQL) installed.
2. **Backend Configuration:** Update the database credentials in `backend/src/main/resources/application.properties`.
3. **Run Backend:** Navigate to `/backend` and execute `./mvnw spring-boot:run`.
4. **Launch Frontend:** Open `frontend/index.html` in your web browser (or serve it using a local live server).
