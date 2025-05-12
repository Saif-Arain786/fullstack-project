


# Fullstack Project

This is a fullstack web application with separate **client** and **server** folders.  
The **client** is built with React.js and Axios, and the **server** is built using Node.js, Express, and MongoDB. A custom middleware is implemented for security.

---

## 📁 Project Structure

```

fullstack-project/
├── client/   ← React.js frontend
└── server/   ← Node.js + Express backend with MongoDB

````

---

# Getting Started

### 1. Clone the Repository

```bash
git clone --recurse-submodules https://github.com/Saif-Arain786/fullstack-project
cd fullstack-project
````

---

## 🖥️ Running the Server


```bash
cd server
npm install
npm start
```

This will start the server at `http://localhost:5004` (or the port you configured).

---

## 🌐 Running the Client

> The client integrates API calls using Axios to the server running locally.

```bash
cd ../client
npm install
npm run dev
```

This will start the VITE-React app at `http://localhost:5000`.

---

# Security

The backend uses **custom middleware** to protect routes and handle authentication or request validation logic securely.

---

##  Testing API

To test the server-side APIs:

1. Ensure the server is running.
2. The client frontend is already configured to call those APIs via Axios.
3. Run the client to interact with and test the backend through the UI.

---

##  Technologies Used

### Client

* React.js
* Axios

### Server

* Node.js
* Express.js
* MongoDB
* Custom Middleware (for security)

---

