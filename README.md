# Rental Store

This repository follows a backend/frontend/infra layout to keep concerns organized.

## Structure

```
backend/
  src/
    controllers/
    services/
    routes/
    middlewares/
    prisma/
    app.js
  Dockerfile
  package.json
frontend/
  pages/
  components/
  styles/
  package.json
infra/
  k8s/
  cloudrun/
.github/
  workflows/
```

## Backend

From `backend/`, start the API server:

```
cd backend
npm start
```
