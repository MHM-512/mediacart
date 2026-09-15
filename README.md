## 🛒 E-Commerce Platform (Microservices Architecture)
A scalable, modular E-Commerce platform built using a microservices architecture. This project focuses on high availability, independent service scalability, and a modern, responsive user interface.

## 📸 Project Preview
(Replace the links below with your actual screenshot paths)


 Authentication	Product & Cart
	
## 🛠 Tech Stack
Frontend
React.js: Core library for building the user interface.
MUI (Material UI): Component library for clean, responsive design.
React Hook Form & Zod: Efficient form management and schema validation.
Axios: Promised-based HTTP client for API communication.
Context API: Global state management for the shopping cart.
Backend & Infrastructure
Microservices: Decoupled services (User, Product, Cart, Order, etc.).
Docker & Docker Compose: Containerization for environment consistency.
API Gateway: Centralized entry point for routing requests.
## 🚀 Installation Guide
Follow these steps to set up the project locally:

# 1. Prerequisites
Node.js (v18 or higher)
Docker & Docker Compose
# 2. Clone the Repository

`git clone https://github.com/your-username/your-repo-name.git`
cd your-repo-name
# 3. Install Dependencies (Frontend)

`cd frontend`
npm install
# 4. Running the Application
Development mode:


`npm run dev`
Running with Microservices:

To spin up the entire infrastructure via Docker:


`docker-compose up --build`
## 💡 Key Features
Optimized Forms: Used react-hook-form to minimize re-renders and improve performance.
Persistence: Implemented localStorage strategy to ensure the cart persists across page reloads.
Security: Designed with future-proofing in mind, supporting HttpOnly Cookies for JWT authentication.
Modular Codebase: Clean component separation for easier maintenance and testing.

