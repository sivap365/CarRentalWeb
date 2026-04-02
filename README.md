# Car Rental System – Frontend Repo

This is the **React-based Full-stack application** of the Car Rental System built using the MERN stack. The application allows users to register, browse available rental cars, make bookings, and manage their profiles. Admins can manage inventory and bookings through a secure dashboard.

---

## 🔗 Live Demo

👉 [Try it here...](https://car-rental-web-mu.vercel.app/)



## 📌 Features

- 🚘 Browse real-time car listings
- 🔐 User authentication 
- 📅 End-to-end booking workflow
- 📊 Admin dashboard to manage cars and bookings
- 📱 Fully responsive UI



## ⚙️ Tech Stack

- **React.js**
- **Axios**
- **React Router DOM**
- **Tailwind CSS / Bootstrap**
- **Vercel** (for deployment)



## 📦 Installation & Local Setup

> ⚠️ **Make sure the backend server is running locally at `http://localhost:5001` before starting the frontend.**

1. Clone the repository:

```bash
git clone https://github.com/sivap365/CarRentalWeb
cd CarRentalWeb
```

2. Install Dependencies 
```
npm install
```
3. Start the Development Server

```
npm start
```


##  🌐 Backend API

The frontend communicates with a backend API server built using Express and MongoDB.


[Backend repo URL](https://github.com/sivap365/CRBackend)


## Environment Configuration
For Development(`localhost`)
```
// src/axios.js
baseURL: "http://localhost:5001/api"
```

For Production(`Deployment`)
```
// src/axios.js
baseURL: <Your backend deployment link>
```

- `Precaution`: Remember to switch the baseURL depending on whether you are running locally or deploying to Vercel.


##  Project Summary

- Built as part of a full-stack car rental system:

- User roles for admin and regular users

- Booking optimization and intuitive workflows

- API performance improved through efficient queries
