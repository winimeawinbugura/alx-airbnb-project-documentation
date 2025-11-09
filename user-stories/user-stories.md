# Airbnb Clone Backend — User Stories

## Objective
Translate the Use Case Diagram interactions into **user stories**. Each user story represents a core functionality from the perspective of the system's actors: Guests, Hosts, Admins, Payment Gateway, and Email Service. User stories are written in the format:

> As a [role], I want to [action] so that [benefit].

These stories will guide backend development from a user-centric perspective.

---

## **User Stories**

### **1. User Management**
- **User Registration**
  - As a **Guest**, I want to register an account so that I can book properties.
  - As a **Host**, I want to register an account so that I can list my properties.
- **Login & Authentication**
  - As a **User**, I want to log in securely using email and password (or OAuth) so that I can access my account.
- **Profile Management**
  - As a **User**, I want to update my profile information and profile photo so that my account reflects my preferences.

---

### **2. Property Listings Management**
- As a **Host**, I want to add new property listings with details like title, description, location, price, and amenities so that guests can view and book them.
- As a **Host**, I want to edit or delete my property listings so that I can keep my listings up-to-date.

---

### **3. Search & Filtering**
- As a **Guest**, I want to search for properties by location, price range, number of guests, and amenities so that I can find suitable accommodation.
- As a **Guest**, I want the search results to be paginated so that I can navigate large sets of properties easily.

---

### **4. Booking Management**
- As a **Guest**, I want to create bookings for available properties so that I can reserve my stay.
- As a **Guest or Host**, I want to cancel bookings according to policy so that I can manage my reservations.
- As a **Guest or Host**, I want to track the status of bookings (pending, confirmed, canceled, completed) so that I know the progress of my reservations.

---

### **5. Payment Integration**
- As a **Guest**, I want to pay securely for my bookings using a payment gateway so that my transactions are safe.
- As a **Host**, I want to receive automatic payouts after bookings are completed so that I can be compensated promptly.
- As a **Guest or Host**, I want the system to support multiple currencies so that I can transact in my preferred currency.

---

### **6. Reviews & Ratings**
- As a **Guest**, I want to leave reviews and ratings for properties I stay in so that I can share feedback with hosts and other users.
- As a **Host**, I want to respond to reviews so that I can address guest feedback.

---

### **7. Notifications**
- As a **Guest or Host**, I want to receive email and in-app notifications for booking confirmations, cancellations, and payment updates so that I stay informed.

---

### **8. Admin Dashboard**
- As an **Admin**, I want to monitor and manage users, property listings, bookings, and payments so that the platform runs smoothly and securely.

---

## **Repository Structure**

