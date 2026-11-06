# NutriAI Web Frontend

The NutriAI web app is built with React and Vite.

## Requirements

- Node.js and npm
- The NutriAI Django backend running locally or deployed

## Setup

From the repository root, install the frontend dependencies:

```bash
cd myfrontend
npm install
```

Copy `.env.example` to `.env` and set the backend URL and Google OAuth client ID.
For local development, the backend URL is usually `http://localhost:8000`.

Start the Vite development server:

```bash
npm run dev
```

To create a production build:

```bash
npm run build
```
