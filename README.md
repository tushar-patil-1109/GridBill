##  ⚡Electricity Billing System (Java)

- A Java-based Electricity Billing System developed using Core Java, Swing (GUI), and MySQL, designed to automate electricity bill management for customers and administrators.
- The Electricity Billing System is a desktop application that helps electricity departments manage customer details, meter information, bill calculation, and payment records efficiently.
- It replaces manual billing processes with a fast, accurate, and user-friendly system.

---

## 🚀 Features

### 1. 🔐 Authentication
- Secure Admin & User Login
- Role-based access control

### 2. 👤 Customer Management
- Add new customers
- View and update customer details
- Store meter information

### 3. ⚡ Billing Management
- Calculate electricity bills based on units consumed
- Generate monthly electricity bills
- View previous bill history

### 4. 💳 Payment System
- Pay electricity bills
- View payment and deposit details

### 5. 🧾 Reports & Records
- Bill details
- Deposit/payment history
- Meter information tracking

--- 

## 🛠️ Technologies Used

- Java (Core application logic)
- Java Swing (GUI development)
- MySQL (Database management)
- JDBC (Database connectivity)
- NetBeans (IDE Development environment)

---

## 📂 Project Structure

```text
Electricity-Billing-System/
│
├── src/
│   └── electricity/billing/system/
│       ├── Login.java
│       ├── NewCustomer.java
│       ├── CustomerDetails.java
│       ├── MeterInfo.java
│       ├── CalculateBill.java
│       ├── GenerateBill.java
│       ├── PayBill.java
│       ├── BillDetails.java
│       ├── DepositDetails.java
│       └── Conn.java
│
├── build/
├── icons/
└── build.xml
```

---

## 🗄️ Database Configuration

- Database Name: ebs
 Database: MySQL
- Connection File: Conn.java
  
```text
DriverManager.getConnection(
    "jdbc:mysql:///ebs",
    "root",
    "password"
);
```
-⚠️ Update username/password as per your local MySQL setup.

---

## ▶️ How to Run the Project (NetBeans)

- 1. Download or clone the repository
- 2. Open NetBeans IDE
- 3. Click File → Open Project
- 4. Select the Employee-Management-System folder
- 5. Configure MySQL database
- 6. Run Splash.java or Login.java

---

## 📸 Application Screenshots

### 1.👤 Admin Dashboard

- ### 🔐 Login Page
<img width="784" height="367" alt="Screenshot 2026-02-05 001052" src="https://github.com/user-attachments/assets/8df2762c-ab2c-46d2-86f0-97279ebf3298" />
</br> <br>

- ### 👤 Add New Customer
<img width="900" height="600" alt="Screenshot 2026-02-05 001123" src="https://github.com/user-attachments/assets/1260df67-f06b-4e1f-b174-91376d94bbc3" />
</br> <br>

- ### ⚡ Calculate Electricity Bill
<img width="900" height="600" alt="Screenshot 2026-02-05 001204" src="https://github.com/user-attachments/assets/f070103c-0465-4381-afdc-a6218dc2e1c4" />
</br> <br>

- ### 💳 Deposite Details
<img width="900" height="900" alt="Screenshot 2026-02-05 001149" src="https://github.com/user-attachments/assets/5163f0c5-de69-4166-977d-8c63858427d7" />
</br> <br>

- ### 📄 Bill Details
<img width="900" height="900" alt="Screenshot 2026-02-05 001355" src="https://github.com/user-attachments/assets/b545e782-f0fb-446c-a570-a28314b36bb2" />
</br> <br>

### 2.👤 Customer Dashboard

- ### 🔐 Login Page
<img width="784" height="367" alt="Screenshot 2026-02-05 001248" src="https://github.com/user-attachments/assets/ca82c6d0-5c10-4c50-ac87-0574024d9f37" />
</br> <br>

- ### 🧾 View Customer Information
<img width="1046" height="804" alt="Screenshot 2026-02-05 001336" src="https://github.com/user-attachments/assets/fd02eec0-2228-4df4-b533-4a80655f6e04" />
</br> <br>

- ### ✏️ Update Customer Information

<img width="900" height="600" alt="Screenshot 2026-02-05 001325" src="https://github.com/user-attachments/assets/0ab11f17-4bc4-4309-afca-eb4bfc522dc3" />
</br> <br>

- ### ⚡ Calculate Electricity Bill
<img width="900" height="600" alt="Screenshot 2026-02-05 001204" src="https://github.com/user-attachments/assets/0c3cf06e-a70f-442b-bec1-e4b7d74b0edd" />
</br> <br>

- ### 💳 Pay Bill

<img width="900" height="600" alt="Screenshot 2026-02-05 001347" src="https://github.com/user-attachments/assets/61617edd-4240-47fc-b80d-96219c13932e" />
</br> <br>

- ### 📄 Bill Details

<img width="600" height="900" alt="Screenshot 2026-02-05 001639" src="https://github.com/user-attachments/assets/95df4037-cdb9-48cb-a7dd-85ac1a3beb87" />
</br> <br>

---

## 🎯 Use Cases

- Electricity department billing automation
- Academic mini/major project
- Java Swing & JDBC practice
- Resume project for Java developers

---

## 📈 Future Enhancements

- Online payment gateway integration
- PDF bill generation
- Role-based dashboards
- Web-based version using Spring Boot
- Advanced billing analytics

---

## 👨‍💻 Author Tushar Patil

- 🎓 Computer Engineering Graduate
- 💻 Java | SQL | Data Structures | OOP

---
