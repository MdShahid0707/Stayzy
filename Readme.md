Stayzy 🏡

Stayzy is a full-stack property listing platform inspired by Airbnb. Users can create, browse, edit, and manage property listings with image uploads, location mapping, authentication, and review functionality.

Features

- User Authentication (Signup/Login/Logout)
- Create, Edit, and Delete Listings
- Upload Property Images using Cloudinary
- Interactive Maps with Geoapify & MapLibre
- Property Reviews and Ratings
- Session Management with MongoDB Store
- Flash Messages for User Feedback
- Responsive UI using EJS Templates

Tech Stack

Backend

- Node.js
- Express.js
- MongoDB
- Mongoose

Authentication

- Passport.js
- Passport Local Strategy
- Passport Local Mongoose

File Uploads

- Multer
- Cloudinary
- Multer Storage Cloudinary

Frontend

- EJS
- EJS-Mate
- CSS
- JavaScript

Other Libraries

- Joi (Validation)
- Connect Flash
- Express Session
- Connect Mongo

---

Project Structure

Stayzy/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
│   ├── css/
│   └── js/
├── utils/
├── init/
├── app.js
├── middleware.js
├── schema.js
└── cloudConfig.js

---

Installation

1. Clone the Repository

git clone https://github.com/yourusername/stayzy.git
cd stayzy

2. Install Dependencies

npm install

3. Create Environment Variables

Create a ".env" file in the root directory:

ATLAS_DB_URL=your_mongodb_connection_string

SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret

MAP_TOKEN=your_geoapify_api_key

4. Run the Application

node app.js

or

nodemon app.js

The application will start on:

http://localhost:8080

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
