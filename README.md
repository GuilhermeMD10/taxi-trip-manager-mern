Taxi Trip Manager (Full Stack Web App)

A web application to manage taxi trips, drivers, and customers. Built with Angular.js frontend, Node.js backend, and MongoDB for data storage. Integrates location-based APIs to calculate trip distances and costs.

---

Tech Stack

- Angular.js
- Node.js + Express
- MongoDB + Mongoose
- JavaScript, HTML, CSS
- Location APIs

---

Features

- Register taxis, drivers, and customers
- Start/end driver shifts and trips
- Cancel trips and calculate real vs estimated costs
- Convert address text to coordinates (Geocoding)
- Cost calculation based on distance and custom pricing policies
- API-based location data and distance logic
- MongoDB schemas mapped from TypeScript interfaces

---

How to Run

1. Clone the repo:

```bash
git clone https://github.com/GuilhermeMD10/taxi-trip-manager-mern.git
cd taxi-trip-manager
```

2. Install backend dependencies and run:

```bash
cd server
npm install
npm start
```

3. Install frontend dependencies and run:

```bash
cd ../client
npm install
npm start
```

> Make sure to configure any required API keys in `.env` or config files.

---

Folder Structure

```
/frontend           # Angular frontend
/backend/taxiCompany         # Node.js backend
```

---

APIs Used

- Google Maps / Geocoding API
- Distance Matrix API

---

