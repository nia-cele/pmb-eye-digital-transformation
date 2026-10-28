# PMB Eye Hospital – Digital Transformation & Policy Portal

> **Executive Case Study & Systems Architecture**  
> *Confidentiality Notice: Proprietary source code, hospital operational credentials, and internal facility data have been omitted in compliance with institutional agreements.*

---

## 📌 Executive Summary
PMB Eye Hospital, a regional specialist ophthalmic facility in Pietermaritzburg, historically managed clinical compliance policies, emergency response protocols, and staff onboarding through physical paper binders. 

This engagement scoped, architected, and delivered a unified, cross-platform digital operational system:
* **Native Android App (Kotlin):** Instant mobile access for floor staff to search clinical guidelines and digitally acknowledge policy updates.
* **Administrative Portal (ASP.NET Core MVC):** Centralized governance hub for management to publish guidelines, manage roles, and monitor compliance.
* **Cloud Backend (Docker + GCP + PostgreSQL):** Containerized RESTful Web API deployed to Google Cloud Run with relational data persistence.

---

## 🔍 The Operational Shift

| Dimension | Before (As-Is) | After (To-Be) |
| :--- | :--- | :--- |
| **Policy Distribution** | Manual print and physical filing | Instant single-click publishing |
| **Compliance Auditing** | Paper sign-off sheets with visibility gaps | Automated real-time audit logging per employee ID |
| **Information Access** | Stationary physical binders across hospital wards | Mobile-first access at point of care |
| **Version Integrity** | High risk of staff referencing obsolete prints | Single source of truth via cloud synchronization |

---

## 🛠️ Architecture & Core Deliverables
<img width="1616" height="366" alt="11111 drawio" src="https://github.com/user-attachments/assets/73b67881-64e3-4a9b-a20b-905520173fea" />

* **Requirements Elicitation:** Mapped user journeys across clinical staff and hospital administration to translate regulatory compliance needs into system features.
* **End-to-End Implementation:** Engineered cross-platform role-based access control (RBAC), database normalization, and containerized cloud deployment.
* **Enablement & Delivery:** Formulated operational standard operating procedures (SOPs) and delivered live system demonstrations to institutional panels.

---

## 🧰 Tech Stack
* **Frontend & Mobile:** Kotlin (Android Studio), ASP.NET Core MVC, Bootstrap
* **Backend & Database:** C# (.NET 10 Web API), Entity Framework Core, PostgreSQL
* **Cloud & DevOps:** Docker, Google Cloud Run, Git/GitHub
* **UI/UX Design:** Canva

---

## File Structure
```plaintext
pmb-eye-digital-transformation/
├── README.md                          <-- The primary showcase (executive summary, diagrams, outcomes)
├── docs/
│   ├── PMB_Eye_Executive_Case_Deck.pdf <-- Export of your presentation slide deck
│   └── system-architecture.png         <-- High-level block diagram (presented to client)
└── assets/
    ├── app-mockup-overview.png         <-- Sanitized UI mockups (Canva exports, no private data)
    └── workflow-comparison.png         <-- As-Is vs. To-Be process diagram
