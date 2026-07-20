# MegaBlog

A modern blog application built with React, focused on scalable architecture, authentication, and reusable components. This project is currently under active development, and this repository reflects the implementation completed so far.

## Project Overview

MegaBlog is a React-based application that emphasizes clean project structure, component reusability, state management, and backend integration. The current implementation establishes the application's foundation, including authentication, routing, reusable UI components, and form management.

## Current Features

- User authentication
  - Sign Up
  - Login
  - Logout
  - Persistent authentication state
- Protected and public route handling
- Global state management using Redux Toolkit
- Form validation and management with React Hook Form
- Reusable UI components
  - Button
  - Input
  - Select
  - Container
  - Header
  - Footer
  - Logo
- Appwrite integration for authentication
- Environment-based configuration
- Responsive UI using Tailwind CSS
- Initial project structure for future blog functionality

## Tech Stack

- React
- Vite
- React Router DOM
- Redux Toolkit
- React Hook Form
- Appwrite
- Tailwind CSS
- JavaScript (ES6+)

## Project Structure

```
src/
├── appwrite/
│   ├── auth.js
│   └── config.js
├── components/
│   ├── Header/
│   ├── Footer/
│   ├── Container/
│   ├── Button/
│   ├── Input/
│   ├── Select/
│   ├── Logo/
│   └── ...
├── conf/
├── store/
├── pages/
├── assets/
├── App.jsx
└── main.jsx
```

> The structure may evolve as additional features are implemented.

## Getting Started

### Prerequisites

- Node.js
- npm
- Appwrite project

### Installation

```bash
git clone <repository-url>

cd MegaBlog

npm install

npm run dev
```

Create a `.env` file and configure your Appwrite credentials before running the application.

## Current Progress

Completed:

- Project setup with Vite
- Routing configuration
- Appwrite authentication setup
- Redux authentication state management
- Protected route implementation
- Authentication forms using React Hook Form
- Reusable UI component architecture
- Base application layout

Planned:

- Rich text editor integration
- Blog post creation
- Post editing
- Image upload
- Complete CRUD operations
- Additional application pages
- Deployment

## Status

This project is currently in progress. The repository represents the implementation completed so far and will continue to be updated as new features are added.

## Acknowledgements

This project is a personal implementation created to strengthen my understanding of modern React development. During development, I referred to various online resources and educational content for learning concepts, best practices, and implementation approaches.