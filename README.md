# 🏡 StayBook – Travel Stay Booking Platform

**StayBook** is a full-stack travel accommodation web application inspired by Airbnb.  
Users can browse listings, book stays, host properties, and leave reviews.

---

## 🚀 Features

* 🧭 Explore curated travel listings (Mountains, Cities, Nature Stays, etc.)
* 🔍 Smart location-based search with Mapbox
* 🗓️ Booking system with check-in/check-out functionality
* 📬 Email confirmations for bookings
* ✍️ Leave ratings and reviews for listings
* 🔐 Secure user authentication and session management

---

## ⚙️ Setup

### Prerequisites

* Node.js and npm
* MongoDB (local or Atlas)

### Installation

```bash
git clone https://github.com/sarikkhan/StayBook.git
cd StayBook
npm install


### Environment Variables

Create a `.env` file in the root folder with:

```env
DB_URL=your_mongodb_connection_string
MAPBOX_TOKEN=your_mapbox_token
SESSION_SECRET=your_session_secret
```

---

## ▶️ Run the App

```bash
npm start
```

Visit: `http://localhost:3000`

---

## 📂 Project Structure

```
StayBook/
├── controllers/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
├── models/
│   ├── booking.js
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── routes/
│   ├── bookings.js
│   ├── listings.js
│   ├── users.js
│   └── search.js
├── views/
│   ├── listings/
│   ├── includes/
│   └── layouts/
├── public/
│   ├── css/
│   │   └── style.css
│   └── js/
│       ├── map.js
│       ├── search.js
│       └── script.js
├── .env (not committed)
├── .gitignore
├── package.json
├── app.js
└── README.md

```
## 📸 Screenshot
![image](![alt text](image.png))
![image](![alt text](image-1.png))

---

## 🙌 Acknowledgements

* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)
* [EJS](https://ejs.co/)
* [Mapbox](https://www.mapbox.com/)
* [Bootstrap](https://getbootstrap.com/)

---

## 📬 Contact

**Sarik Khan**
📧 Email: [sarik2056@gmail.com](mailto:Sarik2056@gmail.com)
🔗 GitHub: [sarikkhan](https://github.com/sarikkhan)

---

> Made with ❤️ for Web Development and learning.
=======
