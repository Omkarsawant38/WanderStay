# 🌍 Wanderlust

**Wanderlust** is a full-stack web application built with **Node.js**, **Express.js**, **MongoDB**, and **EJS**. It allows users to create, read, update, and view listings of travel destinations or accommodations — like hotels, hostels, or homestays.

## 📸 Live Demo
      Link:-https://wanderstay-i4bd.onrender.com/listings

## 📸 Demo



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
   git clone https://github.com/yourusername/wanderlust.git
   cd wanderlust/MajorProject

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


   

