# Merlin AI Assignment

A full-stack web application for tracking Instagram accounts and analyzing baby-related content, built for the Merlin Innovation Team assignment.

## Features
- **User Authentication:** Secure signup and login with JWT.
- **Instagram Tracker:** Track up to 3 public Instagram accounts per user, get notified of new followings.
- **BabyCheck:** Analyze Instagram posts for baby-related images using OpenAI.
- **Email Notifications:** Receive alerts when tracked accounts follow new users.
- **Modern Frontend:** React-based UI with protected routes and clean design.
- **Backend:** Node.js, Express, MongoDB, and integration with RapidAPI and OpenAI.

## Project Structure
```
merlin_assignment/
├── backend/        # Node.js/Express API, MongoDB models, services
├── frontend/       # React app, components, pages, public assets
└── README.md       # Project documentation
```

## Setup & Usage
### 1. Clone the repository
```sh
git clone https://github.com/YuvalMaaravi/Merlin-AI.git
cd Merlin-AI
```
### 2. Install dependencies
- Backend:
  ```sh
  cd backend
  npm install
  ```
- Frontend:
  ```sh
  cd ../frontend
  npm install
  ```
### 3. Environment Variables
- Create `.env` files in both `backend` and `frontend` as needed (see `.gitignore`).
- Backend requires:
  - `MONGODB_URI` (MongoDB connection string)
  - `JWT_SECRET` (JWT signing key)
  - `SENDGRID_API_KEY` (for email)
  - `RAPIDAPI_KEY` (for Instagram API)
  - `OPENAI_API_KEY` (for baby image analysis)
### 4. Run the app
- Backend:
  ```sh
  npm start
  ```
- Frontend:
  ```sh
  npm start
  ```
