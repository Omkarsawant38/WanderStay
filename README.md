# 🌍 Wanderlust

**Wanderlust** Developed a full-stack web application inspired by Airbnb that enables users to list, update, and manage properties, along with viewing and posting reviews. Implemented secure user authentication with Passport.js and added interactive maps using Mapbox for precise, location-based listings. Structured the backend using the MVC pattern and RESTful APIs for modularity, and used MongoDB for efficient storage and management of user, listing, and review data.

Technologies: Node.js, Express.js, MongoDB,Mapbox,Passport.js, Cloudinary, RESTful APIs.

## 📸 Live Demo
         https://wanderstay-i4bd.onrender.com/listings


## 🚀 Features

- 🌐 **Browse Listings** – View all added listings with details.
- 📝 **Add New Listing** – Create a new travel accommodation listing.
- 🔍 **View Details** – Click any listing to view its detailed information.
- ✏️ **Edit Listing** – Modify listing information.
- ❌ **Delete Listing** – (To be implemented) Remove any listing from the database.
- 📄 **EJS Templates** – Clean, dynamic HTML views using EJS and EJS-Mate.

## 🛠 Tech Stack

| Technology      | Usage                     |
|-----------------|---------------------------|
| Node.js         | Server-side runtime       |
| Express.js      | Web framework             |
| MongoDB         | Database                  |
| Mongoose        | ODM for MongoDB           |
| EJS             | Template engine           |
| EJS-Mate        | Layout support for EJS    |
| Method-Override | Supports PUT/DELETE forms |

## 🗂 Project Structure

MajorProject/
├── app.js # Main server file
├── models/
│ └── listing.js # Mongoose schema for listings
├── init/
│ └── data.js # Sample data seeding script
├── views/
│ └── listings/ # EJS templates for views
├── public/ # Static assets (CSS, JS, images)
├── package.json
└── README.md


## ⚙️ Installation & Setup

1. **Clone the repository:**
   git clone https://github.com/Omkarsawant38/WanderStay.git
   cd wanderStay/MajorProject

2. Install dependencies:
   npm install

3. Set up MongoDB:
    Ensure MongoDB is running locally on:
    mongodb://127.0.0.1:27017/wanderlust
   
4. Run the application:
   node app.js

5. Visit in browser:
   http://localhost:3000

## 📸 Screenshots:

1. Login Page:

   <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/bce2e94c-0075-4e53-ad8f-26afe19140e6" />

2. Add New Listing:

   <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/bec0ddd3-08ef-4a11-8547-3feb095d3fd2" />

3. Listing Page:

   <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/4d08200f-ae50-4a01-bf1f-ebcc03e06609" />

4. Edit Listing:

   <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/086ea1c8-a4b5-4754-84bf-f0d37686d45d" />


5. About Listing:

   <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2162dd82-dfa0-4451-8786-2d673f8804a8" />

6. Listing-Location:

   <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1f4aad0d-7844-4828-b4d5-330b691424fe" />


💡 Author
Made with ❤️ by Omkar Sawant





   


   

