# Task Manager MERN Application

A full-stack task management application built with the MERN stack (MongoDB, Express.js, React, Node.js) featuring authentication, filtering, sorting, and pagination.

## Features

### Core Features
- ✅ Create, read, update, and delete tasks
- ✅ Task status tracking
- ✅ Responsive Material-UI design

### Advanced Features
- 🔐 User Authentication
  - JWT-based authentication
  - Register/Login functionality
  - Protected routes
  - User-specific tasks

- 🔍 Search & Filtering
  - Search tasks by title
  - Filter by completion status
  - Sort by title, creation date, or status
  - Ascending/descending order options

- 📄 Pagination
  - Page-based navigation
  - Configurable items per page
  - Total pages calculation

## Tech Stack

### Frontend
- React 18
- Redux Toolkit (State Management)
- Material-UI (Component Library)
- Axios (API Client)

### Backend
- Node.js & Express.js
- MongoDB & Mongoose
- JWT Authentication
- Express Validator

## Project Structure

```
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Auth/
│   │   │   │   ├── LoginForm.jsx
│   │   │   │   └── RegisterForm.jsx
│   │   │   └── Tasks/
│   │   │       ├── TaskForm.jsx
│   │   │       ├── TaskList.jsx
│   │   │       ├── TaskFilters.jsx
│   │   │       └── TaskPagination.jsx
│   │   ├── store/
│   │   │   ├── authSlice.js
│   │   │   ├── taskSlice.js
│   │   │   └── store.js
│   │   └── App.jsx
│   └── package.json
│
├── backend/
│   ├── models/
│   │   ├── Task.js
│   │   └── User.js
│   ├── routes/
│   │   ├── tasks.js
│   │   └── users.js
│   ├── middleware/
│   │   └── auth.js
│   ├── server.js
│   └── package.json
```

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local instance or MongoDB Atlas URI)
- npm or yarn






1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
