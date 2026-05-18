# 🦷 Dentwise – Dental Platform with AI Voice Agent

<p align="center">
  <img src="/public/screenshot-for-readme.png" alt="Dentwise Banner" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-38BDF8?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

---

# 🚀 Overview

**Dentwise** is a modern AI-powered dental platform that helps users easily book dental appointments online while providing AI-powered patient support through a voice assistant.

Built with modern technologies like **Next.js**, **TypeScript**, **Tailwind CSS**, and **PostgreSQL**, the platform delivers a smooth and scalable experience for both patients and administrators.

---

# ✨ Features

## 🏠 Modern Landing Page

* Responsive modern UI
* Smooth gradients and animations
* Service showcase sections
* Mobile-friendly design

---

## 🔐 Authentication System

Authentication powered by Clerk:

* Google Login
* GitHub Login
* Email & Password Login
* Secure Session Management
* Email Verification (6-digit code)

---

## 📅 Appointment Booking System

### 🦷 3-Step Booking Flow

1. Select Dentist
2. Choose Service & Time
3. Confirm Appointment

### Features

* Real-time booking
* Appointment management
* Booking confirmation emails
* Smart scheduling system

---

## 🗣️ AI Voice Agent

AI Voice Assistant powered by Vapi:

* Appointment support
* AI patient interaction
* Automated responses
* Voice-based assistance
* Available for Pro Plans

---

## 💳 Subscription & Payments

Subscription system includes:

* Free Plan
* Premium Plan
* Enterprise Plan

### Payment Features

* Secure payments
* Automatic invoices
* Smart plan upgrades
* Pay only the price difference

---

## 📊 Admin Dashboard

Admins can:

* Manage appointments
* Track users
* Handle bookings
* Manage subscriptions
* Monitor appointment status

---

# 🛠️ Tech Stack

| Technology     | Usage              |
| -------------- | ------------------ |
| Next.js        | Frontend & Backend |
| TypeScript     | Type Safety        |
| Tailwind CSS   | Styling            |
| Shadcn UI      | Components         |
| Clerk          | Authentication     |
| PostgreSQL     | Database           |
| TanStack Query | Data Fetching      |
| Resend         | Email Service      |
| Vapi           | AI Voice Agent     |
| CodeRabbit     | PR Optimization    |
| Sevalla        | Deployment         |

---

# 📂 Project Structure

```bash
dentwise/
│
├── app/
│   ├── (auth)/
│   │   ├── sign-in/
│   │   └── sign-up/
│   │
│   ├── dashboard/
│   │   ├── appointments/
│   │   └── subscriptions/
│   │
│   ├── booking/
│   │
│   ├── admin/
│   │   ├── users/
│   │   ├── bookings/
│   │   └── analytics/
│   │
│   ├── api/
│   │
│   ├── layout.tsx
│   └── page.tsx
│
├── components/
│   ├── ui/
│   ├── booking/
│   ├── dashboard/
│   ├── forms/
│   └── shared/
│
├── hooks/
│
├── lib/
│   ├── auth.ts
│   ├── db.ts
│   ├── utils.ts
│   └── query-client.ts
│
├── prisma/
│   └── schema.prisma
│
├── public/
│   ├── screenshot-for-readme.png
│   └── logo.png
│
├── services/
│
├── styles/
│
├── .env
├── package.json
├── tailwind.config.ts
├── next.config.js
└── README.md
```

---

# ⚙️ Environment Variables Setup

Create a `.env` file in the root directory:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

DATABASE_URL=your_postgres_database_url

NEXT_PUBLIC_VAPI_ASSISTANT_ID=your_vapi_assistant_id
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key

ADMIN_EMAIL=your_admin_email

RESEND_API_KEY=your_resend_api_key

NEXT_PUBLIC_APP_URL=your_app_url
```

---

# 📦 Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/dentwise.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd dentwise
```

---

## 3️⃣ Install Dependencies

```bash
npm install
```

---

## 4️⃣ Setup Prisma Database

```bash
npx prisma migrate dev
```

---

## 5️⃣ Start Development Server

```bash
npm run dev
```

---

# 🌐 Open in Browser

```bash
http://localhost:3000
```

---

# 🔑 Demo Login Details

## 👨‍⚕️ Admin Account

```bash
Email: admin@dentwise.com
Password: admin123
```

---

## 👤 User Account

```bash
Email: user@dentwise.com
Password: user123
```

---

# 📸 Screenshots

## 🏠 Home Page

```bash
/public/screenshot-for-readme.png
```

---

# 🚀 Deployment

You can deploy the application on:

* Vercel
* Netlify
* Railway
* Sevalla

---

# 🤝 Contributing

Contributions are welcome.

## Steps to Contribute

```bash
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit changes
5. Push to GitHub
6. Open Pull Request
```

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Made with ❤️ by Fulbabu Islam
