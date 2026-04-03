🔐 NexusAuth-ZT

Centralized Zero-Trust Identity Provider using Keycloak (IAM Project)

NexusAuth-ZT is a centralized Identity and Access Management (IAM) solution built using Keycloak, implementing Zero-Trust security principles, OIDC authentication, RBAC authorization, Multi-Factor Authentication (MFA), and security hardening controls.

This project simulates a production-style enterprise identity provider capable of securing multiple applications through a unified authentication platform.

---

📌 Project Objective

Organizations often suffer from password fatigue and inconsistent authentication policies across multiple internal applications.

NexusAuth-ZT solves this by:

- Centralizing identity management
- Enforcing secure authentication policies
- Implementing MFA protection
- Providing role-based authorization
- Applying auditing and monitoring controls
- Following Zero-Trust security architecture principles

---

🏗️ Architecture Overview

Key Components:

- Keycloak Identity Provider
- Dockerized Deployment
- PostgreSQL-ready Architecture (Production Pattern)
- OIDC Authentication Flow
- JWT Token Validation
- RBAC Authorization Model
- Conditional MFA (OTP)
- Event Logging & Security Hardening

---

⚙️ Technologies Used

- Keycloak
- Docker
- OpenID Connect (OIDC)
- JWT Tokens
- Role Based Access Control (RBAC)
- Multi-Factor Authentication (OTP)
- Security Headers
- Event Logging & Monitoring

---

📅 Project Implementation Timeline

Week 1 — Identity Infrastructure Setup

✔ Dockerized Keycloak deployment
✔ Infotact realm creation
✔ Roles configuration (Admin / Developer / Viewer)
✔ Users and groups setup
✔ Permanent admin configuration

---

Week 2 — OIDC Integration

✔ OIDC client registration
✔ Flask protected application integration
✔ Redirect-based authentication flow
✔ JWT token generation and validation

---

Week 3 — RBAC + MFA Implementation

✔ Role mapping configuration
✔ Access token claim verification
✔ OTP-based Multi-Factor Authentication
✔ Protected route authorization testing

---

Week 4 — Security Hardening & Auditing

✔ Permanent admin account setup
✔ User event logging enabled
✔ Admin event logging enabled
✔ Token lifespan reduction
✔ Security headers configuration
✔ Brute-force protection enabled

---

🔐 Security Features Implemented

Centralized authentication

OIDC token-based access control

Multi-Factor Authentication (OTP)

Role-based authorization (RBAC)

Short-lived access tokens

Brute-force attack protection

User & admin activity auditing

Browser security header protection

Zero-Trust identity architecture simulation

---

📊 Screenshots Evidence

Project screenshots are available inside:

/screenshots

They include:

- OIDC client configuration
- JWT token validation
- MFA setup
- Role mapping
- Event logging configuration
- Token hardening settings
- Brute force protection setup

---

🚀 Future Enhancements

Google Workspace Federation (Social Login)

WebAuthn Passwordless Authentication

SIEM Integration for log monitoring

Reverse Proxy Deployment (NGINX)

Production TLS Hardening

---

Cybersecurity Project
Identity & Access Management (IAM)
Zero-Trust Authentication Architecture
