# Fullstack Scheduling Calendar SaaS Platform - Meetly

A comprehensive scheduling and calendar management SaaS platform built with modern web technologies.

## 📌 Project Overview

A comprehensive scheduling platform that allows users to book and manage meetings efficiently, featuring calendar integration and automated scheduling capabilities.

---

## 🌟 Key Features

- 🔑 Secure authentication with JWT
- 📅 Event creation and management (public/private)
- 🔗 Unique booking links for easy scheduling
- ⏳ Availability management and time slot booking
- 🌍 Time zone detection and handling
- 📆 Custom calendar interface
- 🔄 Third-party calendar integration
- ✅ Meeting tracking and history
- 🕰️ Multiple time format support
- 💻 Modern full-stack architecture

## 🚀 Tech Stack

- **Node.js** - Scalable backend architecture
- **React.js** - Dynamic frontend framework
- **PostgreSQL** - Robust database solution
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Modern styling framework
- **Vite.js** - Fast build tool and dev server

---

## 🔄 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- PostgreSQL database
- Google Calendar API credentials (optional)

### Installation

1. Install dependencies:
```bash
npm install
```

2. Set up environment variables by creating a `.env` file:
```bash
PORT=8000
NODE_ENV=development
DATABASE_URL="your_postgresql_connection_string"
JWT_SECRET="your_jwt_secret_key"
JWT_EXPIRES_IN="1d"
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
FRONTEND_ORIGIN=http://localhost:5173
```

3. Run the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:8000`.

---

## 🌐 Deployment

1. Set up your environment variables on your hosting platform
2. Deploy using your preferred hosting service (Vercel, Netlify, Render, etc.)
3. Ensure your database is properly configured for production

The application is ready for deployment on any modern hosting platform that supports Node.js applications.
