# ✂️ Vip Hair Designer - Salon Management & Booking System

<div align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
</div>

<br />

Welcome to the **Vip Hair Designer** full-stack web application! This platform provides a seamless booking experience for customers and a comprehensive management dashboard for salon administrators. Built with modern web technologies, it offers a high-performance, secure, and visually premium interface.

## ✨ Features

### 🤵 For Customers (Frontend)
- **Premium User Interface:** A modern, dark-themed, and responsive design tailored for a luxury barber experience.
- **Easy Online Booking:** Step-by-step appointment scheduling.
- **Real-time Availability:** Seamlessly check available slots (powered by React Query).
- **Service & Portfolio Showcase:** Beautiful presentation of haircuts, beard styling, and luxury grooming packages.
- **SEO Optimized:** Built-in JSON-LD schemas and SSR metadata for maximum search engine visibility.

### 🛡️ For Administrators (Backend & Admin Panel)
- **Secure Authentication:** JWT-based login and protected routes for the admin dashboard.
- **Appointment Management:** View, approve, or cancel incoming customer appointments.
- **Dynamic Scheduling System:** Advanced slot calculation using Redis caching to prevent double-booking.
- **Database Migrations:** Version-controlled database schema management using Flyway.

---

## 🛠️ Technology Stack

### Frontend (Client)
- **Framework:** [Next.js 16](https://nextjs.org/) (App Router) + React 19
- **Language:** TypeScript
- **Styling:** [Tailwind CSS 4](https://tailwindcss.com/)
- **State Management:** [Zustand](https://zustand-demo.pmnd.rs/) + [TanStack React Query](https://tanstack.com/query/latest)
- **Icons:** Lucide React

### Backend (Server)
- **Framework:** [Spring Boot 3.3](https://spring.io/projects/spring-boot) (Java 21)
- **Database:** PostgreSQL
- **Caching:** Redis (Redisson)
- **Security:** Spring Security + JWT (JSON Web Tokens)
- **Database Migrations:** Flyway
- **Tools:** Lombok, MapStruct

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
Make sure you have the following installed on your local machine:
- Node.js (v18 or higher)
- Java 21 (JDK)
- PostgreSQL
- Redis
- Maven (or use the provided Maven wrapper)

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/vip-hair-designer.git
cd vip-hair-designer
```

### 2. Backend Setup (`berber-backend`)
1. Navigate to the backend directory:
   ```bash
   cd berber-backend
   ```
2. Update your `application.yml` or `application.properties` with your PostgreSQL and Redis credentials.
3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```
*(Flyway will automatically run database migrations on startup.)*

### 3. Frontend Setup (`berber-frontend`)
1. Open a new terminal and navigate to the frontend directory:
   ```bash
   cd berber-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env.local` file and set the necessary environment variables (like your API base URL).
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3002](http://localhost:3002) in your browser.

---

## 🏗️ Project Structure

```
Vip Hair Designer/
├── berber-frontend/      # Next.js 16 Client Application
│   ├── app/              # App Router (Pages & Layouts)
│   ├── components/       # Reusable UI Components
│   └── types/            # TypeScript Definitions
│
└── berber-backend/       # Spring Boot API
    ├── src/main/java/    # Java Source Code (Controllers, Services, Repositories)
    ├── src/main/resources/ # Configuration & Flyway Migrations
    └── pom.xml           # Maven Dependencies
```

---

## 🎨 Design Philosophy
The design language focuses on **"Lüksün Zirvesi"** (The Pinnacle of Luxury). It utilizes deep dark backgrounds (`#0A0A0A`) with elegant gold and champagne accents (`#D4AF37`, `#F5E6BE`). Smooth micro-animations and blur effects create a dynamic yet sophisticated user experience.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

---
*Crafted with ❤️ for Vip Hair Designer.*
