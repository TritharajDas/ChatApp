# ChatApp Deployment Guide

## Backend Setup
1. Copy `.env.example` to `.env` and fill in all required values.
2. Install dependencies:
   ```sh
   cd backend
   npm install
   ```
3. Start the server:
   ```sh
   npm start
   ```

## Frontend Setup
1. Install dependencies:
   ```sh
   cd frontend
   npm install
   ```
2. Build the frontend:
   ```sh
   npm run build
   ```

## Environment Variables
- See `.env.example` for all required variables.
- Set `CLIENT_URL` to your deployed frontend URL.
- Set `FRONTEND_DIST_PATH` if your deployment structure differs.

## Common Deployment Issues
- Ensure all environment variables are set in your deployment platform.
- Update CORS origins for production.
- Remove any local file dependencies in `package.json`.
- Make sure your database and Cloudinary credentials are correct.

---

For more help, see the code comments or contact the maintainer.
# ChatApplication
