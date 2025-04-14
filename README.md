
# Coloniser Approval System

The **Coloniser Approval System** is a digital platform developed for the **Housing and Environment Department (NIC, Chhattisgarh)** to streamline and digitize the colony development application process. This system enables colonizers to apply, upload documents, and track approvals online in a structured multi-step workflow.

---

## 🎯 Objective

To build a secure and transparent single-window system that automates the approval process for colony development, ensuring timely and consistent decisions across multiple levels of government verification.

---

## 🧩 Key Modules

1. **Applicant Dashboard** – Form submission & document upload.
2. **ADM Verification** – Initial review and final approval/rejection.
3. **Executive Engineer (CSEB NOC)** – Electrical safety compliance.
4. **SDM (EWS Verification)** – Affordable housing check.
5. **Deputy Director (TNCP)** – Layout verification and fee processing.

---

## ⚙️ System Design

- Developed using the **Prototype Model** for iterative improvement.
- Centralized database with structured tables for users, applications, uploaded files, and audit logs.
- Designed for clear data flow across user roles using DFDs and ER diagrams.

---

## 🛠️ Tech Stack

- **Frontend:** Angular 17, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MariaDB (MySQL compatible)
- **File Handling:** Multer (for uploads)

---

## 📦 Setup & Deployment

### Requirements:
- Node.js
- MariaDB
- Angular CLI

### Setup:
```bash
npm install
ng serve
```
