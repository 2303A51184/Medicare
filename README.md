# Medicare Project

[![Build Status](https://github.com/2303A51184/Medicare/actions/workflows/deploy.yml/badge.svg)](https://github.com/2303A51184/Medicare/actions/workflows/deploy.yml)

This repository contains a Medicare application with three main folders:

- `admin/` — Admin frontend application
- `backend/` — Node/Express API server
- `frontend/` — Customer-facing React/Vite frontend

## Push to GitHub

To push this project into the repository at `https://github.com/2303A51184/Medicare`, run these commands from the project root:

```powershell
cd "C:\Users\bonag\Downloads\pcG8M26CrhnQvoDMEV7NPj (1)\MEDICARE"
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/2303A51184/Medicare.git
git branch -M main
git push -u origin main
```

## Deploy

### Frontend

The `frontend/` folder is a Vite React app.

Recommended deploy options:

- Vercel
- Netlify
- GitHub Pages

### Backend

The `backend/` folder is a Node.js Express server.

Recommended deploy options:

- Railway
- Render
- Heroku

## Notes

- Install Git locally before pushing.
- After pushing, configure your chosen hosting service to serve the frontend and backend as needed.
- The repo should then be live at the deployment service URL.
