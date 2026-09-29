# VERO — Verifiable Events & Research Observatory

VERO is a lightweight, real-time intelligence monitoring platform. It aggregates global geopolitical developments, diplomatic shifts, and economic policies into a streamlined, noise-free interface using live data feeds.

## Operational Architecture
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas (Mongoose) for secure transmission logging
- **Data Pipeline:** GNews API integration for live global intelligence

## Core Capabilities
- **Live Intelligence Feed:** Real-time data aggregation focusing on international relations.
- **Dynamic Categorization:** Automated tagging (Diplomacy, Military, Economy) based on semantic content parsing.
- **Secure Transmission Channel:** Direct encrypted database routing for user reports and access requests.
- **Persistent Uptime:** Integrated `/ping` endpoint configured for cron-job keep-alive services.

## Deployment Setup
1. Clone the repository and install dependencies (`npm install`).
2. Configure `.env` with `PORT`, `GNEWS_API_KEY`, and `MONGODB_URI`.
3. Initialize the server via `node server.js`.
