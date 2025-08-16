# MERN Social Media Platform

A full-stack social media application built with the MERN stack (MongoDB, Express, React, Node.js).  
Features include user authentication, posts, likes, comments, friend system, and profile management.

---

## Features

- User registration & login (JWT authentication)
- Create, edit, and delete posts
- Like and comment on posts
- Add and remove friends
- Responsive UI with Material-UI
- Image upload for posts and profiles

---

## Tech Stack

- **Frontend:** React, Redux, Material-UI
- **Backend:** Node.js, Express
- **Database:** MongoDB (Atlas)
- **File Uploads:** Multer
- **Authentication:** JWT

---

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB Atlas account (or local MongoDB)
- [Render](https://render.com/) account (for deployment)

---

### 1. Clone the Repository

```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2. Backend Setup

```sh
cd server
npm install
```

Create a `.env` file in the `server` folder:

```
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=3001
```

Start the backend server:

```sh
npm start
```

---

### 3. Frontend Setup

```sh
cd ../client
npm install
```

Create a `.env` file in the `client` folder:

```
REACT_APP_API_URL=https://your-backend-url.onrender.com
```

Start the frontend:

```sh
npm start
```

---

## Deployment

### Deploy Backend

1. Push your code to GitHub.
2. Deploy the `server` folder to [Render](https://render.com/) as a **Web Service**.
3. Set environment variables in Render as in your `.env`.

### Deploy Frontend

1. Deploy the `client` folder to [Render](https://render.com/) as a **Static Site**.
2. Set the build command to `npm run build` and publish directory to `build`.
3. Add the environment variable `REACT_APP_API_URL` with your backend Render URL.

---

## Folder Structure

```
mern-social-media-master/
├── client/   # React frontend
├── server/   # Express backend
```

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- [Material-UI](https://mui.com/)
- [Redux](https://redux.js.org/)