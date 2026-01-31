# Melipubly 🚀

Official documentation for the **Melipubly** SaaS platform.

Melipubly is a SaaS application designed to automate product import, publishing, pricing, and synchronization workflows between Amazon, Shopify, and Mercado Libre.

---

## 📌 What is Melipubly?

Melipubly aims to become a multi-tenant SaaS platform that allows users to:

- Import products from Amazon and Walmart
- Apply automated pricing rules
- Synchronize listings with Shopify and Mercado Libre
- Manage local and dropshipping stock
- Handle bulk operations and large catalogs

---

## 🏗️ Current Architecture (Implemented)

- Backend: Django + Django REST Framework
- Database: PostgreSQL
- Cache / queues: Redis
- Infrastructure: AWS EC2
- Containers: Docker
- Reverse proxy: Nginx
- Authentication: JWT (access + refresh tokens)

---

## 🧩 Implemented Modules (Current State)

### Backend
- User authentication (JWT)
- Basic user roles (admin / user)
- Import endpoints structure
- Pricing rules base logic
- Dockerized environment
- AWS EC2 deployment

### Frontend
- UI screens implemented (dashboard, auth, basic flows)
- Connected to backend authentication
- Some flows still static or incomplete

---

## 🧪 Partially Implemented / In Progress

- Amazon import logic (API + extension dependency)
- Pricing rules final logic
- Stock synchronization
- Shopify integration
- Mercado Libre integration

---

## 🧠 Project History & Context (IMPORTANT)

Initial development of Melipubly was carried out by a freelancer (**Taha**), who:

- Set up the initial AWS EC2 infrastructure
- Dockerized the backend services
- Implemented authentication and base backend structure
- Delivered frontend UI screens
- Left the project **partially completed**

⚠️ Important notes:
- The project was left **mid-development**
- Some frontend screens are not fully connected to backend logic
- Some architectural decisions were not fully documented
- Further development requires reviewing and validating existing code

This repository exists to **document the current state**, avoid repeating mistakes, and allow new developers to continue the project with full context.

---

## 📁 Repository Scope

This repository contains **documentation only**.

Code repositories:
- `melipubly-backend`
- `melipubly-frontend`
- `melipubly-chrome-extension`

---

## 📌 Project Status (Real)

- [ ] Chrome Extension (not implemented)
- [ ] Amazon import logic (partial)
- [ ] Shopify integration (pending)
- [ ] Mercado Libre integration (pending)
- [ ] Pricing rules engine (partial)
- [ ] Stock synchronization (pending)

---

## 🧠 Final Note

Any developer joining this project **must review the existing backend and frontend code before adding new features**.

This documentation is intended to provide transparency, technical context, and continuity for future development.
