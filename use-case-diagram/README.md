# 🎭 Airbnb Backend Use Case Diagram

## 📘 Objective
This document presents a **Use Case Diagram** illustrating the key interactions between users and the Airbnb backend system.  
It visualizes how different types of users — **Guests**, **Hosts**, and **Admins** — interact with the system’s main features such as **user authentication**, **property management**, **booking**, and **payments**.

The diagram is created using **Draw.io** and exported as:
📄 `use-case-diagram/airbnb_use_case_diagram.png`

---

## 🧍 Actors (System Users)

| Actor | Description |
|-------|--------------|
| **Guest** | A registered user who can browse, book properties, make payments, and leave reviews. |
| **Host** | A user who lists and manages properties on the platform. |
| **Admin** | A system administrator who monitors users, bookings, and payments. |
| **System** | The Airbnb backend that handles authentication, data management, and transactions. |

---

## 🧩 Main Use Cases

### 🧑‍💻 User Authentication
- **Sign Up / Register:** Create a new user account.  
- **Login / Logout:** Authenticate user access securely.  
- **Manage Profile:** Update personal details (name, email, password, phone, etc.).  

---

### 🏠 Property Management (Host)
- **Add Property:** Create a new property listing with description, location, and price.  
- **Edit Property:** Update property details.  
- **Delete Property:** Remove a listing from the platform.  
- **View Property List:** Display all properties owned by the host.  

---

### 📅 Booking System (Guest)
- **Search Property:** Browse and filter available properties.  
- **View Property Details:** Check property information and reviews.  
- **Book Property:** Reserve a property for specific dates.  
- **Cancel Booking:** Cancel a reservation before the start date.  
- **View Booking History:** Review all past and current bookings.  

---

### 💳 Payment Management
- **Make Payment:** Complete a booking payment using available methods (Credit Card, PayPal, Stripe).  
- **View Payment History:** Review past payment transactions.  
- **Refund / Cancellation Payment:** Handle refund requests for canceled bookings.  

---

### 🌟 Reviews & Feedback
- **Add Review:** Write a review for a property after a completed stay.  
- **Edit / Delete Review:** Modify or remove existing reviews.  
- **View Reviews:** Browse reviews for each property.  

---

### 🧑‍💼 Admin Operations
- **Manage Users:** Approve, suspend, or delete accounts.  
- **Manage Properties:** Oversee all listings and remove inappropriate ones.  
- **Monitor Bookings:** Track all reservations and their statuses.  
- **Oversee Payments:** Review transactions and handle disputes.  
- **Generate Reports:** Analyze system usage, revenue, and feedback.  

---

## 🖼️ Use Case Diagram

The **Draw.io diagram** visually represents:
- All **actors** (Guest, Host, Admin)
- The **system boundary** (Airbnb Backend)
- The **interactions (use cases)** between actors and system functionalities

🖼️ File Location:

![use case diagram](https://github.com/user-attachments/assets/847d4a53-6757-499e-9a71-12116a5c7f31)
