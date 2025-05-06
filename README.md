
---

## 🚀 Getting Started

### Prerequisites

- Node.js & npm
- Angular CLI
- Java 17+
- Maven
- MySQL Server

---

## 🔧 Setup Instructions

### 1️⃣ Backend - Spring Boot

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/voting-system.git
    cd voting-system/backend
    ```

2. Configure MySQL Database:
    ```properties
    # application.properties
    spring.datasource.url=jdbc:mysql://localhost:3306/voting_db
    spring.datasource.username=root
    spring.datasource.password=your_password
    spring.jpa.hibernate.ddl-auto=update
    ```

3. Run the Spring Boot application:
    ```bash
    mvn spring-boot:run
    ```

---

### 2️⃣ Frontend - Angular

1. Navigate to frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the development server:
    ```bash
    ng serve
    ```

4. Open in browser:
    ```
    http://localhost:4200
    ```

---

## 🔐 Features

### Admin
- Create and manage elections
- Add candidates and view vote counts
- Activate/deactivate voting sessions

### Student (Voter)
- Register and login securely
- View active elections
- Cast vote once per election

---

## 📦 API Endpoints

> See full list in backend documentation or Swagger (if enabled)

- `POST /api/auth/register` - Register user
- `POST /api/auth/login` - Authenticate user
- `GET /api/elections/active` - List active elections
- `POST /api/vote` - Submit vote

---

## 📷 Screenshots

*(Add screenshots of key UI pages here if available)*

---

## 🧑‍💻 Contributors

- [Your Name](https://github.com/your-username)

---

## 📄 License

This project is licensed under the MIT License.
