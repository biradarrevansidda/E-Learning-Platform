# E-Learning Platform (ELP) - MERN Based Application

This is a full-stack E-Learning Platform (ELP) application built using the MERN stack (MongoDB, Express, React, Node.js). The ELP allows students to enroll in courses, view content, and track progress. Teachers can manage courses, and administrators have access to user and course management functionalities.

---

## Table of Contents
1. [Project Structure](#project-structure)
2. [Installation](#installation)
3. [Environment Variables](#environment-variables)
4. [Usage](#usage)
5. [Features](#features)
    - [User Features](#user-features-students)
    - [Teacher Features](#teacher-features)
    - [Admin Features](#admin-features)
6. [Tech Stack](#tech-stack)
7. [Project Demo Video](#project-demo-video)

---

## Project Structure

The project is organized into two main folders:

### Frontend
Contains the front-end React code for the ELP application:

- **`src/assets/Images`**: Stores images used in the frontend.
- **`src/components/admin`**: Contains components for admin functionalities.
- **`src/components/common`**: Contains common components like login, dashboard, and navbar.
- **`src/components/user/student`**: Contains components for student-specific views.
- **`src/components/user/teacher`**: Contains components for teacher-specific views.

### Backend
Contains the back-end Node.js and Express code for the ELP:

- **`config/`**: Database configuration.
- **`controllers/`**: Contains controllers for admin and user operations.
- **`middlewares/`**: Authentication middleware.
- **`routers/`**: Contains route definitions for admin and user routes.
- **`schemas/`**: Mongoose schemas for database models.
- **`uploads/`**: Stores uploaded files (e.g., course materials).

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/biradarrevansidda/E-Learning-Platform.git
cd Online_learning_platform
```

### 2. Install Dependencies

#### Server
```bash
cd backend
npm install
```

#### Client
```bash
cd frontend
npm install
```

---

## Environment Variables

Create a `.env` file in the backend folder and add the following variables:

```plaintext
MONGO_DB=mongodb://localhost:27017/ELP
PORT=5000
JWT_KEY=my_super_secret_key_123456
```

- **MONGO_DB**: The MongoDB connection string.
- **PORT**: The server port (default: 5000).
- **JWT_KEY**: Secret key for JSON Web Token (JWT) authentication.

---

## Usage

### Running the Server
The server will run on port 5000.

```bash
cd backend
node index.js
```

### Running the Client
The client will start on port 3000 by default.

```bash
cd frontend
npm start
```

---

## Features

### User Features (Students)
- **Course Enrollment**: Students can enroll in courses.
- **View Courses**: Students can access course content and track their progress.
- **Enrolled Courses**: View a list of all courses they’re enrolled in.

### Teacher Features
- **Course Management**: Teachers can add, update, and delete courses.
- **Course Content**: Teachers can upload content for their courses.

### Admin Features
- **User Management**: View and manage all registered users.
- **Course Management**: View and manage all courses available on the platform.
- **Banner Management**: Add and manage banners on the platform (e.g., promotional images).

---

## Tech Stack

- **Frontend**: React, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Token (JWT)

---

## Project Demo Video

Here’s a quick demo showcasing the main features and functionality of the E-Learning Platform. This video walks through the user experience, highlighting both student and teacher functionalities, as well as admin features.

![Watch the output video](#)
- https://drive.google.com/file/d/15UELKcdRCkgHwP1dZG5mDVaZsHs4cMse/view?usp=drivesdk
---

