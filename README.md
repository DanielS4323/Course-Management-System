# 📚 Course Management System - React TypeScript CRUD Application

A modern, full-featured course management platform built with React and TypeScript. This application provides a seamless experience for managing educational courses with role-based access control, allowing administrators to create, update, and delete courses while providing regular users with an intuitive interface to browse and explore course offerings.

## 🎯 Overview

This is a comprehensive CRUD (Create, Read, Update, Delete) application designed for managing courses in an educational setting. The application features a clean, responsive user interface with robust state management and secure authentication. It demonstrates modern React development practices including TypeScript for type safety, Redux for state management, and React Router for seamless navigation.

## ✨ Key Features

### 🔐 Authentication & Authorization
- User registration and login system
- Token-based authentication with secure storage
- Role-based access control (Admin vs Regular User)
- Protected routes for admin-only operations

### 📖 Course Management
- **View Courses**: Browse all available courses with search functionality
- **Course Details**: View comprehensive course information including authors, duration, and descriptions
- **Create Courses**: Admins can create new courses with title, description, duration, and authors
- **Update Courses**: Edit existing course information
- **Delete Courses**: Remove courses from the system
- **Author Management**: Add new authors and assign them to courses
- **Search & Filter**: Search through courses to find specific content

### 🛠 Technical Features
- **State Management**: Redux Toolkit for predictable state management
- **Type Safety**: Full TypeScript implementation for enhanced code reliability
- **Routing**: React Router with public and protected route configurations
- **Error Handling**: Error boundaries and comprehensive error management
- **Form Validation**: Client-side validation for all user inputs
- **Code Quality**: ESLint configuration with pre-commit hooks via Husky

## 🚀 Technologies Used

- **Frontend Framework**: React 18
- **Language**: TypeScript
- **Build Tool**: Vite
- **State Management**: Redux Toolkit
- **Routing**: React Router v6
- **Code Quality**: ESLint, Prettier, Husky
- **Additional Libraries**: React Error Boundary, UUID

## 📋 Prerequisites

Before running this application, ensure you have:

- Node.js (v16 or higher recommended)
- npm or yarn package manager
- A backend server running on `http://localhost:4000` (API endpoints for courses, authors, and authentication)

## 🏃 Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Course-CRUD-App
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview production build**
   ```bash
   npm run preview
   ```

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── Courses/        # Course listing and management
│   ├── CourseInfo/     # Course detail view
│   ├── Header/         # Application header
│   ├── Login/          # Authentication
│   └── Registration/   # User registration
├── store/              # Redux store configuration
│   ├── courses/        # Course state management
│   ├── authors/        # Author state management
│   └── user/           # User/auth state management
├── routes/             # Route configurations
├── helpers/            # Utility functions
├── common/             # Reusable UI components
└── services.ts         # API service configurations
```

## 👥 User Roles

### Regular User
- View all courses
- Search courses
- View course details

### Admin User
- All regular user capabilities
- Create new courses
- Update existing courses
- Delete courses
- Manage course authors

## 🔧 Development

- **Linting**: `npm run lint`
- **Fix linting issues**: `npm run eslint:fix`

## 📝 License

This project is part of a learning course and is intended for educational purposes.

---

Built with ❤️ using React, TypeScript, and Redux
