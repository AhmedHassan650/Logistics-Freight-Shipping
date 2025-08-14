# Container Yard Management System (CYMS)
## Online demo 
https://ahmedhassan650.github.io/Logistics-Freight-Shipping/


## Overview
The **Container Yard Management System** is a web-based application designed to manage the full operations of a container yard facility.  
It enables yard operators to track container inventory, manage rentals, monitor financial transactions, handle shipping details, and generate operational reports — all from a browser interface.

This system is built entirely with **HTML, CSS, and JavaScript**, making it lightweight and easy to deploy on platforms like **GitHub Pages** or any web server.

---

## Features & Pages

### 1. **Login Page** (`login.html`)
- **Purpose:** Provides secure access to the system.
- **Key Features:**
  - Username/password input fields.
  - Redirects authenticated users to the main Dashboard.
- **Flow:** User enters valid credentials → navigates to Dashboard.

---

### 2. **Dashboard** (`index.html`)
- **Purpose:** Serves as the central hub for navigation and quick stats.
- **Key Features:**
  - Displays **Key Metrics** (e.g., number of containers, rentals, revenue).
  - Navigation links to all main modules.
- **Flow:** Acts as the starting point after login, with shortcuts to Container Management, Financials, Rentals, Shipping, and Reports.

---

### 3. **Container Management** (`container_management.html`)
- **Purpose:** Manage all containers stored in the yard.
- **Key Features:**
  - Add, edit, and delete container records.
  - Track container type, ID, status, and location.
- **Flow:** Operators use this module to maintain up-to-date container inventory.

---

### 4. **Financial Management** (`financial_management.html`)
- **Purpose:** Manage and review all financial transactions.
- **Key Features:**
  - View **financial reports**.
  - Print current financial summaries.
  - Monitor rental payments, operational costs, and revenue.
- **Flow:** Allows financial staff to generate and print monthly or custom reports.

---

### 5. **Rental Management** (`rental_management.html`)
- **Purpose:** Track and manage container rentals.
- **Key Features:**
  - Manage rental agreements.
  - Track rental durations, due dates, and charges.
- **Flow:** Used by rental desk to update status and payments for active rentals.

---

### 6. **Shipping Management** (`shipping_management.html`)
- **Purpose:** Handle shipping and transportation operations.
- **Key Features:**
  - Manage outbound and inbound shipping details.
  - Track shipping schedules and assigned containers.
- **Flow:** Logistics team uses it to ensure timely shipping operations.

---

### 7. **Reports** (`reports.html`)
- **Purpose:** Generate operational and financial reports.
- **Key Features:**
  - Print **current operational** or **financial reports**.
  - Track metrics over time.
- **Flow:** Used by management for strategic decision-making.

---

## Navigation Flow
1. **Login** → **Dashboard**
2. From **Dashboard**, navigate to:
   - Container Management
   - Financial Management
   - Rental Management
   - Shipping Management
   - Reports
3. Each section has data entry, tracking, and print/export functionality.

---
## Online Demo
https://ahmedhassan650.github.io/Logistics-Freight-Shipping/
   # Using Python
   python -m http.server 8000
