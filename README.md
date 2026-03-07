
# 🚇 Metro Ticket Generating System – ServiceNow Project

## 📌 Overview
The **Metro Ticket Generating System** is a ServiceNow-based application designed to simulate a digital metro ticket booking platform.  
It allows users to book metro tickets through a **Service Portal**, automatically processes the request using **Flow Designer**, stores ticket details in a **custom database table**, and generates a **QR code** for ticket validation at metro stations.

This project demonstrates how ServiceNow can be used to build automated service applications using Service Catalog, UI Policies, Client Scripts, and workflow automation.

---

## ✨ Features

- Metro ticket booking through **Service Portal**
- Selection of **Source and Destination stations**
- **Dynamic fare calculation**
- **Passenger input handling**
- **QR code generation for ticket validation**
- Ticket details stored in a **custom Metro database table**
- **Flow Designer automation** for request processing
- **Form validation using Catalog Client Scripts**
- **UI Policies for dynamic form behavior**
- **Access Control Rules (ACLs)** for security

---

## ⚙️ System Workflow

1. User opens the **Service Portal**
2. Selects **Book a Metro Ticket**
3. Fills in ticket details:
   - Source Station  
   - Destination Station  
   - Number of Passengers  
   - Journey Type  
4. The system calculates the **fare automatically**
5. User clicks **Submit**
6. **Flow Designer workflow executes**
7. Ticket data is stored in the **Metro Ticket Database table**
8. A **QR code ticket is generated**
9. The QR code can be scanned at the metro station

---

## 🛠 Technologies Used

- ServiceNow **Service Catalog**
- ServiceNow **Service Portal**
- **Flow Designer**
- **Catalog Client Scripts**
- **UI Policies**
- **Custom Tables**
- **Access Control Rules (ACLs)**
- **QR Code API Integration**

---

## 🚀 Setup Instructions

1. Log in to your **ServiceNow Personal Developer Instance (PDI)**
2. Create a **Service Catalog Item** named **Book a Metro Ticket**
3. Add catalog variables:
   - Source Station
   - Destination Station
   - Passenger Count
4. Create a **Custom Table – Metro Ticket Database**
5. Configure **Flow Designer workflow**
6. Map catalog variables to database fields
7. Implement **QR code generation logic**
8. Configure **ACL rules for access control**
9. Test ticket submission from the **Service Portal**

---

## 🔮 Future Enhancements

- Online **Payment Gateway Integration**
- **SMS / Email ticket delivery**
- **Metro usage analytics dashboard**
- **Mobile application integration**
- Support for **multiple metro networks**

---
