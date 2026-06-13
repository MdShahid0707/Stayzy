Stayzy 🏡

Stayzy is a full-stack property listing platform inspired by Airbnb where users can discover, create, manage, and review property listings.

🚀 Live Demo

Website: https://stayzy-agxz.onrender.com

Explore the deployed application and browse listings, create accounts, add properties, upload images, and leave reviews. The site is currently hosted on Render.

---

Features

- User Authentication (Signup/Login/Logout)
- Create, Edit & Delete Listings
- Property Image Uploads
- Interactive Location Mapping
- Reviews & Ratings System
- Session-Based Authentication
- Responsive User Interface
- Flash Messages & Error Handling

Tech Stack

Frontend

- EJS
- HTML5
- CSS3
- Bootstrap
- JavaScript

Backend

- Node.js
- Express.js

Database

- MongoDB
- Mongoose

Authentication

- Passport.js
- Passport Local Strategy
- Passport Local Mongoose

Cloud Services

- Cloudinary (Image Storage)
- Geoapify (Geocoding API)
- MapLibre (Maps)

---

Installation

Clone Repository

git clone https://github.com/MdShahid0707/stayzy.git
cd stayzy

Install Dependencies

npm install

Configure Environment Variables

Create a ".env" file:

ATLAS_DB_URL=your_mongodb_uri

SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_key
CLOUD_API_SECRET=your_cloudinary_secret

MAP_TOKEN=your_geoapify_api_key

Run Locally

npm start

or

nodemon app.js

Visit:

http://localhost:8080

---

Project Structure

Stayzy
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── utils/
├── middleware.js
├── schema.js
├── cloudConfig.js
├── app.js
└── package.json

---

Core Functionalities

Listings

- Browse all available properties
- View detailed listing information
- Create and manage listings
- Upload property images

Reviews

- Add reviews and ratings
- Delete own reviews

Authentication

- Secure registration and login
- Route protection
- Persistent sessions

Maps

- Convert locations to coordinates
- Display listings on interactive maps

---

Future Enhancements

- Advanced Search & Filters
- Wishlist/Favorites
- Property Booking System
- Payment Integration
- User Profiles
- Admin Dashboard

---

Screenshots

Add screenshots of:

- Home Page
- Listing Details Page
- Create Listing Page
- Login & Signup Pages

---

Author

Mohd Aamir

Built with Node.js, Express.js, MongoDB, Cloudinary, Geoapify, and MapLibre.
---

Database Setup

To seed sample listings:

node init/index.js

---

Key Functionalities

Listings

- View all listings
- Create new listings
- Edit existing listings
- Delete listings
- Upload property images

Reviews

- Add reviews to listings
- Delete reviews
- Rating system support

Authentication

- User registration
- User login
- Protected routes
- Session persistence

Maps Integration

- Converts listing locations into coordinates using Geoapify Geocoding API.
- Displays property locations on interactive maps using MapLibre.

---

Future Improvements

- Search and filtering
- Wishlist/Favorites
- Booking functionality
- Payment integration
- User profiles
- Admin dashboard

---

Screenshots

Add screenshots of:

- Home Page
- Listing Details Page
- Create Listing Page
- Authentication Pages

---

License

This project is licensed under the ISC License.

---

Author

Mohd Aamir

Built as a full-stack web development project using Node.js, Express, MongoDB, Cloudinary, and Geoapify.
