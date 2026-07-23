# Express.js Live Dashboard Application

## Overview & Features
This full-stack application features an Express.js backend serving restful API endpoints (`GET /api/items`, `POST /api/items`) connected to a responsive frontend user interface.

### Features
* **RESTful Express API**: Serves and receives JSON responses.
* **Middleware Integration**: Express static serving, `express.json()` parsing, and live logging.
* **Dynamic Environment Variables**: Reads `APP_TITLE` using `process.env`.
* **UX Improvements**: Includes loading indicators, client/server error handling, and animated card components.

## Environment Variables
The application uses the following environment variables:
* `PORT`: Server port (Defaults to `3000`).
* `APP_TITLE`: Displays dynamic title header on frontend.

## Deployment Steps (Render)
1. Commit and push repository to GitHub.
2. Sign in to Render and create a **New Web Service**.
3. Select this repository.
4. Set Build Command to `npm install` and Start Command to `npm start`.
5. Under **Environment Variables**, add:
   * Key: `APP_TITLE`
   * Value: `Production Admin Dashboard`
6. Click **Deploy Web Service** to publish live.

## Screenshots Required for Submission
1. `screenshots/live_app.png`: Showing the live app working in the browser.
2. `screenshots/deployment_env.png`: Screenshot of Render environment variables settings.
