# 🛒 My E-Commerce Platform

A full-stack e-commerce application built with a decoupled architecture, separating the client-side user interface from the server-side business logic.

## 🏗️ Architecture & Tech Stack

This project is organized as a monorepo containing both the frontend and backend ecosystems:

* **Frontend:** Built using **Vite**, React/Vue, Tailwind CSS, and PostCSS for a fast, responsive user interface.
* **Backend:** Built using **Java Spring Boot** managed by Maven (`pom.xml`), handling core business logic, API routing, and database integrations.

---

## 📁 Repository Structure

text```
my-ecommerce-platform/
│
├── frontend/               # Vite configuration, UI components, assets
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── backend/                # Java Spring Boot application files
│   ├── src/
│   └── pom.xml
│
└── README.md               # Main project documentation
```

---

## 🚀 Getting Started

### Prerequisites
* **Node.js** (v18+ recommended)
* **Java Development Kit (JDK)** (v17 or higher recommended)
* **Maven** (or use the included `./mvnw` wrapper)

### 💻 Running the Frontend
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install the necessary dependencies:
   ...bash
   npm install
   ...
3. Start the local development server:
   ...bash
   npm run dev
   ...

### ☕ Running the Backend
1. Navigate to the backend directory:
   ...bash
   cd backend
   ...
2. Build and run the Spring Boot application using the Maven wrapper:
   ```bash
   ./mvnw spring-boot:run
   ```

---

## 🛠️ Key Features Implemented
* **Decoupled Architecture:** Clean separation of concerns between frontend and backend.
* **Modern UI:** Utility-first styling utilizing **Tailwind CSS**.
* **Fast Development:** Built on **Vite** for near-instant hot module replacement (HMR).
* **Enterprise Backend:** Robust server environment powered by **Spring Boot**.
*
