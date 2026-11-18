
# 🚀 AstroVault

<p align="center">
  <b>A Multi-Tenant SaaS Platform for Space Research Document Management</b>
</p>

<p align="center">
  Built with Flask and PostgreSQL
</p>

---

## 🌌 Overview

**AstroVault** is a multi-tenant Software-as-a-Service (SaaS) platform designed for managing space research documents in an organized and structured environment.

The platform aims to provide a centralized system for storing, organizing, and managing research-related documents while supporting multiple tenants within a shared application infrastructure.

Built using **Flask** and **PostgreSQL**, AstroVault focuses on structured data management, backend development, and multi-tenant application architecture.

---

## 🎯 Problem Statement

Space research involves handling large volumes of scientific documents, reports, research papers, and related resources.

Managing these documents across different research teams and organizations can become challenging without a centralized and structured platform.

AstroVault aims to address this by providing a SaaS-based document management solution designed around multi-tenant architecture.

---

## ✨ Key Objectives

- 📁 Centralized space research document management.
- 🏢 Multi-tenant SaaS architecture.
- 🔐 Structured tenant-aware data management.
- 🗄️ Relational database management using PostgreSQL.
- ⚙️ Backend application development using Flask.
- 📈 A scalable foundation for research document management.

---

## 🏗️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| PostgreSQL | Relational database |
| SQL | Database queries and management |
| Git & GitHub | Version control |

---

## 🧩 System Architecture

AstroVault follows a web-based application architecture.

```text
          Users / Organizations
                   |
                   v
          Flask Application
                   |
          Tenant-aware Logic
                   |
                   v
              PostgreSQL
                   |
                   v
        Structured Data Storage
```

---

## 📂 Project Structure

```text
ASTROVAULT/
│
├── app/
│   ├── routes/
│   ├── models/
│   ├── services/
│   └── __init__.py
│
├── config/
│
├── migrations/
│
├── tests/
│
├── requirements.txt
├── .env.example
├── .gitignore
├── run.py
└── README.md
```

*Note: Update this structure to match the actual project directories.*

---

## ⚙️ Getting Started

### Prerequisites

- Python 3.x
- PostgreSQL
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/ThanushaPrakash/ASTROVAULT.git
```

### 2. Navigate to the Project

```bash
cd ASTROVAULT
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows:**
```powershell
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure Environment Variables

Create a `.env` file and configure the required database connection settings.

```env
DATABASE_URL=your_postgresql_connection_string
SECRET_KEY=your_secret_key
```

### 6. Run the Application

Use the project's configured Flask entry point.

```bash
python run.py
```

---

## 🔐 Multi-Tenant Architecture

AstroVault is designed around a multi-tenant SaaS model, where multiple organizations can use the same application infrastructure.

The architecture aims to maintain tenant-specific data organization and separation.

---

## 🛣️ Future Scope

- Advanced document search and filtering.
- Research document categorization.
- Document version management.
- Role-based access control.
- Research collaboration features.
- Cloud-based document storage.
- Analytics and reporting.

---

## 👩‍💻 Author

**Thanusha Prakash**

Computer Science and Engineering | Artificial Intelligence

[GitHub](https://github.com/ThanushaPrakash)

---

<p align="center">
  <i>Organizing knowledge. Empowering space research. 🚀</i>
</p>
