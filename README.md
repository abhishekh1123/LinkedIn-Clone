# Full Stack LinkedIn Clone 

A full-stack MERN application with authentication, posts, profiles, notifications, and connections.

## Tech Stack

- **Frontend**: React, React Router, React Query, Axios, TailwindCSS
- **Backend**: Node.js, Express.js, MongoDB
- **Other**: JWT Auth, Cloudinary, Mailtrap, Cookie-based sessions

## Setup

### .env

Create a `.env` file in the root with:

```bash
PORT=5000
MONGO_URI=<your_mongo_uri>
JWT_SECRET=<yourverystrongsecret>
NODE_ENV=development

MAILTRAP_TOKEN=<your_mailtrap_token>
EMAIL_FROM=mailtrap@demomailtrap.com
EMAIL_FROM_NAME=<Your_Name>

CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>

CLIENT_URL=http://localhost:5173


