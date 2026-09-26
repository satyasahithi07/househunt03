# 🏠 House Hunt

A full-stack property rental platform built to provide a structured
and user-friendly experience for managing and exploring residential
property listings.

## 📌 Project Overview

House Hunt is a full-stack web application developed using React.js
for the frontend and Node.js with Express.js for the backend.

The application follows a role-based structure with separate
functionality for **Administrators, Property Owners, and Users**.

## ✨ Key Features

- Role-based application structure
- Property listing management
- User and owner management
- Secure authentication
- Property image/file uploads
- RESTful backend APIs
- MongoDB-based data management
- Responsive web interface

## 👥 User Roles

### 👨‍💼 Admin

Provides administrative functionality for managing the application
and its users.

### 🏠 Property Owner

Provides functionality for property owners to manage their listings.

### 👤 User

Allows users to explore and interact with available property listings.

## 🛠️ Technologies Used

### Frontend

- React.js
- JavaScript
- HTML
- CSS

### Backend

- Node.js
- Express.js
- REST APIs

### Database

- MongoDB
- Mongoose

### Authentication & Security

- JSON Web Token (JWT)
- bcrypt.js
- CORS
- Environment Variables

### File Handling

- Multer

### Development Tools

- Nodemon
- npm
- Git
- GitHub

## 📂 Project Structure

```text
househunt03/
│
└── Project file/
    │
    ├── frontend/
    │   ├── public/
    │   ├── src/
    │   ├── package.json
    │   └── README.md
    │
    └── backend/
        ├── config/
        ├── controllers/
        │   ├── adminControllers.js
        │   ├── ownerControllers
        │   └── userControllers
        │
        ├── middlewares/
        ├── routes/
        │   ├── adminRoutes.js
        │   ├── ownerRoutes.js
        │   └── userRoutes.js
        │
        ├── schemas/
        ├── uploads/
        ├── index.js
        ├── package.json
        └── package-lock.json
            ```
          ---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- MongoDB

### 1. Clone the Repository

```bash
git clone https://github.com/satyasahithi07/househunt03.git
```

### 2. Set Up the Frontend

Navigate to the frontend directory:

```bash
cd "Project file/frontend"
```

Install the required dependencies:

```bash
npm install
```

Start the React application:

```bash
npm start
```

### 3. Set Up the Backend

Open a new terminal and navigate to the backend directory:

```bash
cd "Project file/backend"
```

Install the backend dependencies:

```bash
npm install
```

Start the backend server:

```bash
npm start
```

### 4. Environment Configuration

Create a `.env` file inside the backend directory and configure the required environment variables.

Example:

```text
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Do not upload real passwords, database credentials, API keys, or secret keys to GitHub.

---

## 📸 Screenshots

Screenshots of the application can be added here to showcase the
frontend interface and major application pages.

---

## 🎯 Project Objective

The House Hunt project was developed to demonstrate practical
full-stack development skills, including frontend development,
backend API development, database integration, authentication,
file handling, and role-based application architecture.

---

## 🔮 Future Enhancements

- Advanced property search and filtering
- Location-based property discovery
- Property booking functionality
- Improved user dashboards
- Notifications and messaging
- Advanced analytics
- Cloud deployment

---

## 👩‍💻 Author

**Satya Sahithi**

- GitHub: [satyasahithi07](https://github.com/satyasahithi07)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/vasamsetti-satya-sahithi/)

---

⭐ Thanks for visiting the House Hunt project!
            
