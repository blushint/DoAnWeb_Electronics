# Electronics E-Commerce Web Application (Team Academic Project)

> Migrated copy of our Web Programming final team project.  
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
> Insert diagrams below. These diagrams were created to explain processes and guide implementation.

### 3.1 Customer Order Workflow (O2C)
![Customer order workflow](docs/diagrams/customer-workflow.png)  
**TODO:** Replace with your workflow diagram.

### 3.2 Admin Order Processing Workflow
![Admin order workflow](docs/diagrams/admin-workflow.png)  
**TODO:** Replace with your workflow diagram.

### 3.3 System Diagrams
- ERD  
  ![ERD](docs/diagrams/erd.png)  
  **TODO:** Replace with your ERD image.
- Use Case Diagram  
  ![Use case](docs/diagrams/usecase.png)  
  **TODO:** Replace with your use case diagram.
- Activity Diagram  
  ![Activity](docs/diagrams/activity.png)  
  **TODO:** Replace with your activity diagram.

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
