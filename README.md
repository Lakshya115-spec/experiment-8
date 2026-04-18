# RBAC Experiment

This project implements Role-Based Access Control with React, React Router, Express, MongoDB, and Mongoose.

## Structure

- `backend/` - Express API with authentication, role middleware, admin and manager routes.
- `frontend/` - React app with protected routes, role-based navigation, and admin UI.

## Run

1. Install dependencies:
   - `npm install`
2. Start backend:
   - `npm run dev:backend`
3. Start frontend:
   - `npm run dev:frontend`

## Default admin

The backend seeds a default admin on first run using environment values or fallback credentials:

- email: `admin@example.com`
- password: `Admin123!`

## Features

- Admin-only dashboard
- Unauthorized user blocking
- Role-based navigation menu
- Permission-controlled APIs
- Manager and user routes
