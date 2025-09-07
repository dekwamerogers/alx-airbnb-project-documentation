# Airbnb Project - User Stories

This document outlines the user stories for the **Airbnb Project** backend system.  
It captures the needs of different users (guests, hosts, and admins) to ensure that  
the backend supports all required features and functionalities.

---

## 📌 Overview

The Airbnb Project aims to provide a robust platform where:

- **Guests** can register, browse properties, make bookings, and leave reviews.
- **Hosts** can manage property listings and view bookings.
- **Admins** can oversee platform activities and ensure smooth operations.

These user stories help guide backend development and ensure that all system functionalities align with user needs.

---

## 🧩 User Stories

### **1. User Registration & Login**

**User Story:**  
_As a guest, I want to create an account and log in securely so that I can book properties and manage my reservations._

- **Priority:** High  
- **Actors:** Guest  
- **Features:**
  - Register with email and password
  - Secure login with credentials
  - OAuth login (Google/Facebook)
  - Profile retrieval

---

### **2. Host Property Listing**

**User Story:**  
_As a host, I want to add and manage my property listings so that potential guests can view and book my accommodations._

- **Priority:** High  
- **Actors:** Host  
- **Features:**
  - Add a new property
  - Upload property images
  - Edit and delete properties
  - View property details

---

### **3. Booking a Property**

**User Story:**  
_As a guest, I want to search for available properties and book them so that I can reserve a place to stay during my travel dates._

- **Priority:** High  
- **Actors:** Guest  
- **Features:**
  - Search for properties by location, price, and availability
  - Make a booking for specific dates
  - Cancel or modify bookings
  - View booking history

---

### **4. Payment Processing**

**User Story:**  
_As a guest, I want to make secure payments for my bookings so that I can confirm my reservation without worrying about fraud._

- **Priority:** Medium  
- **Actors:** Guest  
- **Features:**
  - Multiple payment methods (Card, Mobile Money, PayPal)
  - Secure transactions via SSL
  - Payment confirmation notifications
  - Refund processing

---

### **5. Review & Ratings**

**User Story:**  
_As a guest, I want to leave a review and rating after my stay so that future guests can make informed booking decisions._

- **Priority:** Low  
- **Actors:** Guest  
- **Features:**
  - Leave a review after completed bookings
  - Rate the property on a 5-star scale
  - View reviews of other guests
  - Allow hosts to respond to reviews

---

## 🛠 How to Use This Document

- Use these stories to define backend API endpoints.
- Each story will guide **input validation**, **output formats**, and **security requirements**.
- Prioritize stories based on business needs.

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this document.

---

**Author:** Ebenezer Baafi  
**Project:** Airbnb Project Backend  
