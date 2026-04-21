> # Library-Management-System
This application provides a comprehensive platform for managing library operations, including inventory control, automated book issuance, and membership lifecycle management. It features a role-based access control system to distinguish between administrative capabilities and general user tasks.
> **Core Features**
Role-Based Access Control (RBAC):

**Admin:** Full access to maintenance (Add/Update books and movies), detailed reports, and all transaction modules.

**User:** Restricted access focusing on book searches, transactions, and viewing reports.

**Inventory Management:** Support for both books and movies with mandatory metadata validation.

> **Transaction Logic:**

**Automated Book Issuance:** Automatically populates author details and sets a default 15-day return period.

**Smart Returns:** Integrated "Fine Pay" module that requires verification of payment before a transaction is finalized.

**Membership Management:** Allows for new member registration with flexible plans (6 months, 1 year, or 2 years) and simple membership extensions.

> **System Validations**
**Date Enforcement:** The system prevents users from selecting an issue date earlier than the current day.

**Form Integrity:** Built-in error handling ensures all required fields are populated and selections are made before submission.

**Security:** Password masking is enforced on all login pages to protect user credentials.

> **Technical Implementation**
**Frontend:** A clean, responsive user interface featuring a centralized login modal and intuitive navigation links for instructions and system charts.

**Workflow:** The application uses radio buttons for single-selection tasks (like selecting a book from search results) and checkboxes for mandatory confirmations.

> **UI Preview**
The current implementation features a professional, minimalist login interface that serves as the entry point for both Admins and Users.
