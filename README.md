# TravelMomery

TravelMomery is a web application designed to help users document and share their travel experiences. It allows users to store travel memories, upload photos, and manage their travel data efficiently.

---

## Features
- Connects to MongoDB Atlas for secure and scalable data storage.
- Backend powered by Node.js for robust server-side operations.
- Frontend built with React for a dynamic and responsive user interface.
- Easy setup with `.env` configuration for both backend and frontend.

---

## Getting Started

### Backend Setup
1. Create a `.env` file in the backend directory and configure MongoDB Atlas.
   ```
   MONGO_URI=<Your MongoDB Atlas Connection String>
   ```
   ![Created .env file and configure MongoDB Atlas](image-01-Connecting-Database.png)

2. Install dependencies:
   ```
   npm install
   ```

3. Start the backend server:
   ```
   node backend/index.js
   ```
   ![Backend Output](image-02-Output-node-index.js.png)

4. Add data to the database:
   ![Adding Data to Database](image-03-AddingData.png)

5. Verify the output:
   ![Output](image-04.png)

---

### Frontend Setup
1. Create a `.env` file in the frontend directory with the following content:
   ```
   REACT_APP_BACKEND_URL=http://localhost:3001
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the frontend server:
   ```
   npm start
   ```
   ![Frontend Output](image-05-frontend.png)

---

## Technologies Used
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Frontend**: React.js

---

