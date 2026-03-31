# n8n self-hosted

n8n running on Render with persistent disk storage.

## Render config

- **Build command:** `npm install`
- **Start command:** `npm start`
- **Node version:** 22

## Environment variables

See `.env.example` for required variables. Set these in the Render dashboard.

## Data

Workflows and credentials are stored on the persistent disk at `/mnt/mydisk/n8nData/.n8n`.
