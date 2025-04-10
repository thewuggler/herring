# herring

# 🎨 Art Gallery CRM Platform

A modern, mobile-first platform to help art gallery owners manage their day-to-day business: contacts, inventory, purchases, SMS-based communication, recommendations, and intelligent nudges—all in one place.

---

## 🔧 Tech Stack

| Layer           | Technology                     | Purpose                                  |
|----------------|----------------------------------|------------------------------------------|
| **Backend**     | Python (FastAPI)                | REST API & business logic                 |
| **Database**    | PostgreSQL                      | Relational storage for core entities      |
| **ORM**         | SQLAlchemy                      | Database modeling & migrations            |
| **Frontend (Mobile)** | React Native (Expo)            | Mobile-first experience for gallery owners |
| **Frontend (Web)**    | React + Tailwind CSS           | Web dashboard for office work             |
| **Auth**        | Firebase Auth or Auth0          | User authentication and session mgmt      |
| **Messaging**   | Twilio API                      | SMS messaging layer                       |
| **Deployment**  | Docker + Fly.io / Heroku / AWS  | App hosting and scaling                   |

---

## 📱 Key Features

- **Two-Way SMS Inbox** – Carry on real conversations with collectors.
- **Contact Management** – Keep notes, art preferences, and history in one place.
- **Inventory Management** – Track artwork, artists, and availability.
- **Sales History** – Record what sold to whom and when.
- **Smart Recommendations** – AI + manual suggestions for upselling.
- **Purchase Prediction** – Intelligent nudges to drive timely outreach.
- **Unified Communication Layer** – Combine SMS, email, and task tracking.

---

## 📦 Project Structure
art-gallery-crm/
│
├── backend/                  # FastAPI application
│   ├── app/
│   │   ├── models/           # SQLAlchemy models
│   │   ├── routes/           # API routes
│   │   ├── services/         # Business logic
│   │   └── main.py           # API entry point
│   └── requirements.txt
│
├── mobile-app/               # React Native app
│   ├── components/
│   ├── screens/
│   └── App.js
│
├── web-app/                  # React web dashboard
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── tailwind.config.js
│
├── database/
│   └── migrations/
│
├── docker-compose.yml        # Local dev setup
└── README.md

