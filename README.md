# Electronics E-Commerce Web Application (Team Academic Project)

> Migrated copy of our Web Programming final team project.  The original project can be accessed via https://github.com/quochuy171105/DoAnCuoiKiLapTrinhWeb
> This repository is maintained for portfolio/learning purposes.

## 1. Project Overview
An electronics e-commerce website (similar to ShopDunk) designed as a full MVC-based system.  
The project focuses on **end-to-end business process analysis, functional requirements, and system design**, then implemented by the development team using PHP + MySQL.

**Business Scope**
- User side: account management, product browsing/search/filter, cart & checkout, promotions, feedback, order history.
- Admin side: product/order/promotion management, revenue analytics.

---

## 2. My Role & Contributions (Business Analysis / System Design)
I worked as a **Business Analyst / System Designer** in this project.

**Key contributions**
- **Business Process Analysis**
  - Collected and analyzed user/admin needs.
  - Modeled **AS-IS / TO-BE workflows** for key flows:  
    Order-to-Cash (customer ordering) and Admin order processing.
- **Requirement Engineering**
  - Defined and documented **functional requirements** for:
    - Authentication & profile management
    - Feedback & review management
    - User promotions/discount flow
  - Ensured requirement traceability from business goals to features.
- **System & Data Design**
  - Designed **ERD** and database schema (master data & transaction data).
  - Produced **use cases, activity diagrams, and business flow diagrams** to guide implementation.
- **Collaboration & Validation**
  - Worked with developers to clarify logic and edge cases.
  - Supported test planning by defining expected outputs and scenarios.

---

## 3. Workflow / Diagrams
### 3.1 Workflow Diagram 
#### Customer Order Workflow (O2C)
<img width="620" height="951" alt="image" src="https://github.com/user-attachments/assets/3436c9a0-4743-4618-b5de-7fd3a42dd4f5" />

#### Admin Order Processing Workflow
<img width="499" height="804" alt="image" src="https://github.com/user-attachments/assets/6505d458-187b-4b9d-b541-16cd590d2492" />

### 3.2 Business Functional Diagram
#### Customer Business Functional Diagram  
<img width="528" height="409" alt="image" src="https://github.com/user-attachments/assets/23ee586b-92f4-470f-9616-f3cf7617f3eb" />
#### Member Customer Business Functional Diagram  
<img width="940" height="406" alt="image" src="https://github.com/user-attachments/assets/bd20afdc-397b-4f06-9a85-66cb4f5e07f7" />
#### Admin Business Functional Diagram  
<img width="940" height="404" alt="image" src="https://github.com/user-attachments/assets/5961b1b4-90d5-4e82-a0d3-b941175addab" />

### 3.3 Entity Relationship Diagram
<img width="940" height="913" alt="image" src="https://github.com/user-attachments/assets/57dd4908-c2aa-4633-ad94-124c57022749" />

### 3.4 Class Diagram
<img width="940" height="885" alt="image" src="https://github.com/user-attachments/assets/e0de4b7d-99b9-489c-95ce-8e1d9331ee36" />

---

## 4. Functional Modules

### 4.1 User Modules
- Account: register, login/logout, forgot password, update profile
- Browse products: categories, search, filter, product detail
- Cart & checkout: add/update/remove items, place orders
- Promotions: apply discount codes
- Feedback: submit reviews and view feedback history
- Order tracking: view order history/status

### 4.2 Admin Modules
- Product management (CRUD)
- Order management & status updates
- Promotion management (CRUD)
- Revenue dashboard (charts & tables)

---

## 5. Project Structure (High-level)
```text
DoAnCuoiKiLapTrinhWeb/
├── assets/         # UI resources (CSS/JS/images/libs)
├── config/         # System/database configuration
├── controllers/    # MVC controllers
├── models/         # MVC models (PDO queries)
├── views/          # User + Admin pages + shared layouts
├── services/       # AJAX endpoints (JSON)
├── sql/            # Database schema & seed data
├── index.php       # User entry point
├── admin.php       # Admin entry point
└── README.md
