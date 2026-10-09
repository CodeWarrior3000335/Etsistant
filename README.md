# Etsistant

An easy-to-use AI-assisted product demand and pricing assistant for beginner Etsy sellers.

## About

Etsistant helps makers evaluate a product idea before they make or list it. The planned demo accepts a product photo, description, and making cost, then provides a demand verdict, plain-language reasons, confidence and its basis, suggested prices, and estimated profit. This will later become a SaaS product after the demo has been built.

Etsistant is an independent project and is not affiliated with or endorsed by Etsy.

### Demo scope

The first demo is planned to include:

- Product photo, description, and cost input
- A Strong, Moderate, Weak, or Unclear demand verdict with plain-language reasons
- A confidence level, the signals behind it, and a hint about what could improve it
- A minimum viable price, low/recommended/high price options, and estimated profit
- A standalone profit calculator
- Anonymous use and a responsive desktop/mobile interface

### Planned technology

- Backend: Python, Django, Django REST Framework
- Frontend: React, TypeScript, and Vite
- Database: PostgreSQL on Neon
- Deployment: Render

### Repository structure

- `backend/` — Django API and business logic
- `frontend/` — React web application

### Project status

Initial project setup. The first goal is a working demo. Later on, the SaaS version will include a PWA, product idea comparisons, user accounts, and paid plans.

