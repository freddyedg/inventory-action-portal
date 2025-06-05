# Inventory Action Portal

A lightweight frontend app to submit inventory actions (like RANGE/DERANGE SKUs) via a secure API Gateway. Built to replace Tableau dashboards with a scalable, secure, and EDG-compliant UI.

## Features
- React + TypeScript frontend with form submission
- API Gateway integration with API key header
- Ready for Cloud Run + Docker deployment
- Future-ready for MongoDB + Azure SSO

## Tech Stack
- Frontend: React (Vite + TS)
- Backend: API Gateway + Cloud Run
- Auth: API Key (→ SSO via Azure AD)
- Storage: Google Sheet (temp) → MongoDB (planned)

## Setup
```bash
git clone https://github.com/your-username/inventory-action-portal.git
cd inventory-action-portal
npm install
npm run dev
