ViewI

ViewI is a full-stack video-sharing platform built using the MERN stack (MongoDB, Express.js, React, Node.js).
It enables users to upload, discover, and interact with videos, manage profiles, and receive notifications, similar to a modern video-sharing application.

🚀 Demo

(Add your live frontend URL here)
Example:

https://view-i1.vercel.app

✨ Features

Email Verification
Users must verify their email address before logging in.

Google Authentication
Secure and seamless login using Google OAuth.

Video Upload & Management
Upload, manage, and organize videos using Cloudinary storage.

Video Playback
Modern, responsive video player for smooth viewing.

Search & Discovery
Search videos using keywords with filtered results.

User Profiles
Personalized user profiles to manage uploaded content and account details.

Notifications
Real-time notifications for user interactions.

Responsive UI
Fully responsive design for mobile and desktop devices.

🛠 Tech Stack
Frontend

React

Tailwind CSS

Redux Toolkit (state management)

React Router

React Icons

Backend

Node.js

Express.js

MongoDB

Mongoose

Cloudinary (media storage)

Google OAuth

JWT Authentication

📁 Project Structure
viewI/
├── frontend/
│   ├── src/
│   └── package.json
├── backend/
│   ├── src/
│   └── package.json
└── README.md

⚙️ Local Setup Guide
1️⃣ Clone the Repository
git clone https://github.com/Abhilash107/viewI.git
cd viewI

2️⃣ Frontend Setup
cd frontend
npm install


Create a .env file inside frontend/:

VITE_API_URL=http://localhost:8000
VITE_GOOGLE_CLIENT_ID=<yourGoogleClientID>
VITE_CLOUD_NAME=<yourCloudinaryCloudName>


Start the frontend:

npm run dev

3️⃣ Backend Setup
cd ../backend
npm install


Create a .env file inside backend/:

PORT=8000
MONGODB_URI=<yourMongoDBURI>

ACCESS_TOKEN_SECRET=<yourAccessTokenSecret>
ACCESS_TOKEN_EXPIRY=1d
REFRESH_TOKEN_SECRET=<yourRefreshTokenSecret>
REFRESH_TOKEN_EXPIRY=10d

CLOUDINARY_CLOUD_NAME=<yourCloudinaryCloudName>
CLOUDINARY_API_KEY=<yourCloudinaryApiKey>
CLOUDINARY_API_SECRET=<yourCloudinaryApiSecret>

# Email configuration
EMAIL_USERNAME=<yourEmail>
EMAIL_PASSWORD=<yourEmailAppPassword>
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=465

# Google OAuth
GOOGLE_CLIENT_ID=<yourGoogleClientID>


Start the backend:

npm run dev

4️⃣ Access the Application

Open your browser and visit:

http://localhost:5173

🔐 Authentication Flow

Email + password authentication with verification

Google OAuth login

JWT-based access & refresh tokens

Secure HTTP-only cookies

📦 Deployment

Frontend: Vercel

Backend: Render

Database: MongoDB Atlas

Media Storage: Cloudinary

📌 Future Improvements

Video recommendations

Watch history

Comments threading

Live streaming

Advanced search filters

👤 Author

Abhilash Mishra
GitHub: @Abhilash107