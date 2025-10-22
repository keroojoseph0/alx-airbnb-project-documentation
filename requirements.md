# 🏗️ Airbnb Backend — Requirement Specifications

## 📘 Objective
This document defines the **detailed requirement specifications** for the core backend features of the Airbnb backend system.  
Each feature includes the necessary **API endpoints**, **input/output parameters**, **validation rules**, and **performance criteria** to ensure the system is reliable, scalable, and secure.

---

## 🔐 1. User Authentication

### 📖 Overview
Handles user registration, login, and authentication using secure password hashing and JWT tokens.

### ⚙️ API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/api/auth/register` | Register a new user |
| POST | `/api/auth/login` | Authenticate user and return JWT token |
| GET | `/api/auth/profile` | Retrieve user profile (JWT required) |

### 🧩 Input / Output Specifications

#### ➤ **POST /api/auth/register**
**Input (JSON):**
```json
{
  "first_name": "John",
  "last_name": "Doe",
  "email": "john@example.com",
  "password": "Password123!",
  "phone_number": "+201234567890"
}

