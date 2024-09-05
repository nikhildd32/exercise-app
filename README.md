
# **ExerciseTrack**

A full-stack exercise tracking web application built using the MERN (MongoDB, Express, React, and Node.js) stack. This app allows users to track their exercise routines efficiently, with data stored in MongoDB and hosted on MongoDB Atlas and Google Cloud Platform.

### **Key Features:**

- **Track Exercises:** Log exercises including duration, type, and date.
- **CRUD Functionality:** Users can Create, Read, Update, and Delete exercise entries.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **RESTful API:** Built using Express.js and Node.js to handle backend services.
- **Cloud-Based Database:** The app uses MongoDB Atlas for secure and scalable data storage.
- **Front-End Interface:** Developed with React.js for a dynamic and smooth user experience.

---

## **Technologies Used**

- **MongoDB:** NoSQL database for efficient and flexible data storage.
- **Express.js:** Web framework for building backend REST APIs.
- **React.js:** Frontend library for creating interactive user interfaces.
- **Node.js:** JavaScript runtime environment for backend logic.
- **Mongoose:** Object Data Modeling (ODM) library for MongoDB and Node.js.

---

## **Project Structure**

```bash
.
├── client/                # React Frontend
│   └── src/
│       ├── components/    # Reusable React components
│       └── App.js         # Main React app
├── server/                # Express Backend
│   └── models/            # Mongoose models
│   └── routes/            # API routes
└── package.json           # Project dependencies
```

---

## **Getting Started**

Follow these steps to run the project on your local machine.

### **Prerequisites**

Ensure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn (for package management)
- MongoDB (local or MongoDB Atlas account)

### **Installation**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/exercise-tracker-app.git
   cd exercise-tracker-app
   ```

2. **Install dependencies:**

   Navigate to the root directory and run:

   ```bash
   npm install
   ```

   Then move to the client directory and install frontend dependencies:

   ```bash
   cd client
   npm install
   ```

3. **Configure environment variables:**

   Create a `.env` file in the root directory and configure your MongoDB URI:

   ```bash
   MONGODB_URI=your-mongodb-atlas-uri
   ```

4. **Run the application:**

   In the root directory, start the server:

   ```bash
   npm start
   ```

   Open a new terminal window, navigate to the `client` directory, and run:

   ```bash
   npm start
   ```

   The app will run locally on [http://localhost:3000](http://localhost:3000).

---

## **Deployment**

This application can be deployed on any cloud platform such as Heroku, Vercel, or Netlify. Before deploying, make sure to:

1. Set the production environment variables (MongoDB URI, etc.).
2. Run the following command to build the React app:

   ```bash
   npm run build
   ```

3. Deploy both the frontend (`build/` folder) and backend to your preferred hosting provider.

---

## **Screenshots**

### **Exercise Tracker Interface**
![Exercise Tracker Screenshot](https://github.com/user-attachments/assets/ac44e992-7350-434e-a968-30f6b96b1c5a)

### **Exercise Log**
![Exercise Log Screenshot](https://github.com/user-attachments/assets/e7b4a70b-0b22-42ec-87de-504b6954e255)
