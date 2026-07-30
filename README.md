# SRS Requirement Management System

A full-stack enterprise-grade application designed for managing Software Requirements Specifications (SRS) for the users who wants to build a project they can give requirements through this app to the developers .

## 🚀 Tech Stack

* **Frontend:** React.js, Vite, Axios, Reusable Components
* **Backend:** Spring Boot (v3.5.14), Spring Data JPA, Hibernate, Java 21
* **Database:** Oracle Database 21c Express Edition

---

## 📋 Core Modules

## 📋 System Architecture & Modules

The application is structured into comprehensive enterprise-grade specification and testing modules categorized into three primary functional groups:

### 1. Basic Requirements Module
* **Project Information:** Captures high-level project metadata, versioning, lifecycles, budgets, priorities, and business domains[cite: 1].
* **User Profiles:** Manages user classes, intended groups, clearance levels, permissions, and system access types[cite: 1].
* **Functional Specs:** Handles functional requirement metrics, input parameters, and processing logic descriptions[cite: 1].
* **Non-Functional Specs:** Tracks performance metrics, scalability targets, and availability rate constraints[cite: 1].
* **System Interfaces:** Configures external system connections, interface types, and data formats[cite: 1].

### 2. Design Requirements Module
* **Architecture Models:** Manages tier counts, technology distributions, and high-level system layouts[cite: 1].
* **Module Designs:** Defines module versions, categories, types, and logic architectures[cite: 1].
* **Database Schema:** Configures relational schemas, class mapping definitions, and data persistence indexes[cite: 1].
* **API & Security:** Tracks secure HTTP endpoints, parameter validation rules, and role-based access bounds[cite: 1].
* **UI Navigation Flow:** Maps interactive layout parameters, canvas view boundaries, and dynamic multi-step wizard routes[cite: 1].

### 3. Testing Requirements Module
* **Testing & QA Specifications:** Captures core testing specifications, priority tiers, module contexts, and execution tracking matrices[cite: 1].
* **Automation & Unit Specs:** Manages unit test cases, target class/method signatures, execution runners, and mocking dependencies[cite: 1].
* **Manual & QA Matrix:** Handles UAT sign-offs, manual test procedures, exploratory timeboxes, and team size allocations[cite: 1].
* **Performance & Stress:** Configures load testing engines (k6/JMeter), peak user concurrency (VUs), RPS throughput targets, and response time SLAs[cite: 1].
* **Security & Environments:** Manages CI/CD pipeline security hooks, SAST tool configurations, vulnerability scanning frequencies, and isolated sandbox topologies[cite: 1].

---

## ⚙️ How to Run Locally

### Prerequisites
* Java 21 or higher installed
* Node.js & npm installed
* Oracle Database 21c Express Edition running locally

### 1. Backend Setup (Spring Boot)
1. Navigate to the backend directory:
   ```bash
   cd backend
   Configure your Oracle database credentials in src/main/resources/application.properties.

Run the application using Maven:

Bash
./mvnw spring-boot:run
(The backend server will start on port 8088)

2. Frontend Setup (React)
Navigate to the frontend directory:

Bash
cd frontend
Install dependencies:

Bash
npm install
Start the development server:

Bash
npm run dev
