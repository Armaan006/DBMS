# 🏨 Hotel Booking System (DBMS Project)

## 📌 Project Overview
The **Hotel Booking System** is a database management project designed to automate hotel operations such as reservations, customer management, payments, staff records, and room availability.  
This system reduces manual errors, ensures real-time updates, and improves efficiency for both hotel staff and guests.

---

## 🚀 Features
✅ Centralized data management for customers, rooms, reservations, staff, and payments.  
✅ Real-time room availability updates to prevent double booking.
✅ Secure payment processing (cash, card, online).  
✅ Staff management with role-based responsibilities.  
✅ Multi-branch support for hotel chains.  
✅ Customer history & preferences tracking for better services.

---

## 🗂️ Database Design

### Entities
- **Customer** – Stores customer details, booking history, and preferences.  
- **Hotel Branch** – Each branch has its own staff and rooms.  
- **Room** – Includes type, price, and availability status.  
- **Reservation** – Manages check-in/check-out details.  
- **Staff** – Records employee roles and assignments.  
- **Payment** – Securely records transaction details.  

### Relationships
- **Customer ↔ Reservation** (Many-to-Many)  
- **Reservation ↔ Room** (Many-to-One)  
- **Hotel Branch ↔ Room** (One-to-Many)  
- **Hotel Branch ↔ Staff** (One-to-Many)  
- **Reservation ↔ Payment** (One-to-One)  

---

## 📊 ER Diagram & Schema
The system is modeled using an **ER diagram** and mapped to a **relational schema**, which defines all entities, attributes, and relationships.  

📄 Full documentation is available in [`DBMS_Project_File.pdf`](./DBMS_Project_File.pdf)

---

## 🔎 Example Relational Algebra Queries
Here are some sample queries implemented in the project:

- List details of all available rooms.  
- Show payments greater than ₹5000.  
- Get names of staff working as Receptionists.  
- Find customers who never made a reservation.  
- Show reservations without corresponding payments.  

➡️ See the complete query set in the [Project PDF](./DBMS_Project_File.pdf).  

---

## 🛠️ Tech Stack 
- **Query Language**: Relational Algebra  
- **Documentation**: ER Diagrams, Relational Schema  

---

## 👩‍💻 Team Members
- **Aneet Kaur** (2410990838)  
- **Armaanpreet Kaur** (2410990855)  
- **Arpita Sharma** (2410990859)  
- **Daman Preet Kaur** (2410990115)  

📚 Batch: **2024-28** | 👥 Group No: **G-11**  
📌 Submitted To: *Sachin Garg Sir*  

---

## 📄 Project Report
The detailed documentation, including ER diagrams, relational models, and relational algebra queries, is available here:  
📑 [DBMS_Project_File.pdf](./DBMS_Project_File.pdf)

---

✨ *This repository is part of an academic DBMS project focusing on relational database design and implementation for a Hotel Booking System.*  
