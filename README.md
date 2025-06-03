# 🧠 Mini CRM Platform – Xeno SDE Internship Assignment 2025

This project is a **Mini CRM Platform** built as part of the **Xeno SDE Internship Assignment**. It enables **customer segmentation**, **personalized campaign delivery**, and integrates **AI-powered features** to enhance marketing effectiveness.

---

## 🚀 Assignment Goal

> Build a Mini CRM Platform that enables customer segmentation, personalized campaign delivery, and intelligent insights using modern tools and approaches.

---

## 📚 Table of Contents

- [🔗 Live Demo](#-live-demo)
- [🎥 Demo Video](#-demo-video)
- [✨ Features Implemented](#-features-implemented)
- [🛠 Tech Stack](#-tech-stack)
- [🧱 Architecture Diagram](#-architecture-diagram)
- [⚙️ Getting Started](#️-getting-started)
- [📄 API Documentation](#-api-documentation)
- [🤖 AI Integration](#-ai-integration)
- [⚠️ Known Limitations & Assumptions](#️-known-limitations--assumptions)
- [🔮 Future Scope](#-future-scope)

---

## 🔗 Live Demo

- **Frontend**: [Live Frontend Link](#)
- **Backend**: [Live Backend Link](#)

---

## 🎥 Demo Video

- 📽️ [Watch Demo Video](#)

---

## ✨ Features Implemented

### ✅ Data Ingestion APIs
- Upload customer/order data via CSV.
- Secure REST APIs with backend validations.
- Swagger UI for API testing.

### ✅ Campaign Creation
- **Audience Segmentation**:
  - Define rules using logical conditions (e.g., `spend > 10000 AND visits < 3`).
  - Combine rules with AND/OR logic.
- **Campaign Setup**:
  - Define campaign name, message, and intent.
  - Associate campaigns with segment rules or direct customer selection.

### ✅ Authentication
- Google OAuth 2.0 login.
- Only authenticated users can access segmentation and campaigns.

### ✅ AI-Driven Message Suggestions
- Integrates Google Gemini API.
- Auto-generate campaign messages based on name and audience.

### ✅ Core CRM Features
- View customers and orders.
- List and manage segment rules and campaigns.

---

## 🛠 Tech Stack

### Frontend
- `Next.js (v15+)` with App Router
- `React 19+`
- `TypeScript`
- `Tailwind CSS`, `Ant Design`
- `Zustand` for global state management

### Backend
- `Node.js`, `Express.js`
- `TypeScript`
- `MongoDB` with `Mongoose`

### Authentication
- Google OAuth 2.0
- JWT (via Google ID Token validation)


### AI Integration
- Google Gemini API for message generation

---

## 🧱 Architecture Diagram

