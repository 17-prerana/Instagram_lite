# Instagram Lite

A lightweight social photo-sharing app with a Node.js/Express API and a React frontend.

## Run locally

1. Install the server dependencies with `npm install`.
2. Copy `.env.example` to `.env` and set the required service credentials.
3. Start the API with `npm start`.
4. In `client`, install frontend dependencies with `npm install`, copy `.env.example` to `.env`, and run `npm run dev`.

The API listens on port `5000` by default. Set `PORT` to override it.

## Deployment

For a Node.js web service such as Render, use `npm start` as the start command and configure the server environment variables from `.env.example` in the hosting dashboard. Set `VITE_API_BASE_URL` in the frontend build environment to the deployed API URL followed by `/api`.

Do not commit `.env` files, uploaded files, or runtime logs. Configure MongoDB network access to allow only the required application egress addresses whenever possible.
