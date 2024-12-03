
# Employee Management System (EMS)

An Employee Management System (EMS) built with React.js, featuring a user-friendly dashboard for both employees and administrators. The application uses `useState` for state management and `Context API` for managing authentication and task-related data. It stores data locally for demonstration purposes.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Setup Instructions](#setup-instructions)
4. [File Structure](#file-structure)
5. [Project Workflow](#project-workflow)
6. [Technologies Used](#technologies-used)
7. [Future Improvements](#future-improvements)

---

## Introduction
This project serves as a comprehensive example of building a full-fledged React application with:
- Separate dashboards for employees and administrators.
- Authentication and state management using the Context API.
- Local storage for data persistence.
- Task management functionality.

---

## Features
1. **Employee Dashboard**: Personalized space for employees to view their data and tasks.
2. **Admin Dashboard**: Tools to manage employee tasks and view system-wide data.
3. **Authentication**: Login functionality with user-specific data separation.
4. **Task Management**: Create, update, and manage tasks effectively.
5. **Local Storage Integration**: Persistent data storage without a backend.

---

## Setup Instructions

### Prerequisites
- Node.js and npm installed.
- Basic understanding of React.js.

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/saarthack/ems.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ems
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the application in your browser 

---

## File Structure
```
ems/
├── src/
│   ├── components/           # Reusable components
│   ├── context/              # Authentication and task context
│   ├── pages/                # Employee and Admin pages
│   ├── utils/                # Utility functions
│   └── App.js                # Main application file
├── public/                   # Public files
├── package.json              # Project metadata and dependencies
└── README.md                 # Project documentation
```

---



## Technologies Used
- **Frontend**: React.js
- **State Management**: `useState`, Context API
- **Data Storage**: Local Storage
- **Styling**: CSS, Tailwind (optional)

---

## Future Improvements
1. Integrate a backend API for persistent and scalable data storage.
2. Add role-based authentication for enhanced security.
3. Include test cases to ensure functionality and reliability.
4. Optimize UI for better user experience.

---
