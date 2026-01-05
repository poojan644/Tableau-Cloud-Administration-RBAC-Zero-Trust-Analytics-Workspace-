# Tableau Cloud Administration with RBAC & Zero Trust

## Overview
This project demonstrates the design and administration of a secure
Tableau Cloud environment using Zero Trust security principles and
role-based access control (RBAC).

The focus is on identity-based access, MFA enforcement, and administrative
governance — similar to how enterprise BI platforms are managed in
real-world organizations.

---

## Key Objectives
- Deploy a Tableau Cloud site with secure authentication
- Enforce Zero Trust access using MFA
- Implement RBAC using Tableau site roles
- Manage users, permissions, and governance settings
- Document admin workflows and security decisions

---

## Architecture
📁 See `/architecture/` for the system design diagram.

High-level components:
- Tableau Cloud (SaaS BI Platform)
- Identity-based authentication with MFA
- Role-based access control at site level
- Centralized administrative governance

---

## Implementation Summary
- Created and configured Tableau Cloud site
- Enabled MFA-based authentication
- Added users with least-privilege roles
- Verified role enforcement and access restrictions
- Reviewed site security and governance settings

---

## Project Structure
```text
├── README.md
├── architecture/
│   └── tableau-cloud-architecture.png
├── docs/
│   ├── Setup-Guide.md
│   └── Security-Architecture.md
├── screenshots/
│   ├── authentication-settings.png
│   ├── user-management.png
│   └── site-settings.png


Security Focus
Zero Trust model (identity-first security)
MFA enforced authentication
RBAC using Tableau site roles
Admin-governed site configuration

-Skills Demonstrated
-Tableau Cloud Administration
-Identity & Access Management (IAM)
-RBAC implementation
-Zero Trust security concepts
-SaaS platform governance
-Technical documentation



