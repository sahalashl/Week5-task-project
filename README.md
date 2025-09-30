# Freelance Job Platform - Starter Fullstack Project

Follow Quick Start below to run with seed data.

## Quick Start (with seed data)
1. **Backend**
   ```bash
   cd backend
   npm install
   cp .env.example .env
   npm run seed
   npm run dev   # or npm start
   ```

   Seeded credentials:
   - Admin: `admin@demo.com` / `admin123`
   - User (client): `client@demo.com` / `client123`
   - Freelancer: `freelancer@demo.com` / `freelancer123`

2. **Frontend**
   ```bash
   cd frontend
   npm install
   cp .env.example .env   # optional
   npm start
   ```

## Postman
Import `backend/postman_collection.json`. Set `{{baseUrl}}` and `{{token}}` if needed.
