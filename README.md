# TDD in Legacy Code Transformation

## Context & Purpose

I found [Valentina](https://www.linkedin.com/in/valentinajemuovic/) sharing her thoughts & process on how we can transform legacy codebase into a testable one. And eventually use TDD to gain confidence in software delivery

She is writing a series of articles at [Optivem](https://journal.optivem.com/) which will guide the readers through the entire process.

The purpose is to learn that process.

## Relevant Projects

1. [Tasker UI](https://github.com/naumanzchaudhry/tasker-ui)
2. [Tasker API](https://github.com/naumanzchaudhry/tasker-api)

## Todo Sample App Features

### 1. User Authentication

- Sign up and log in with JWT-based authentication.
- Auto-redirect logged-in users to the dashboard.
- Password hashing and token management.
- Logout

### 2. Task Management

- Create, view, and delete personal todos.
- Each user only sees their own tasks.

### 3. Data Storage

- Uses PostgreSQL via Prisma ORM for database management.

### 4. Error Handling

- Covers common edge cases (e.g., invalid input, authentication errors).
- Clear user feedback for errors.

### 5. [Frontend](https://github.com/naumanzchaudhry/tasker-ui)

- Built with Vue 3 and Pinia for state management.
- Uses the Composition API and styled with Shadcn.
- Axios automatically sets auth tokens for API requests.

### 6. [Backend](https://github.com/naumanzchaudhry/tasker-ui)

- Built with Express.js for API endpoints.
- Prisma ORM for database operations.
- Nodemon for auto-reloading in development.

### Contributors

- [Muaviya](https://github.com/MuaviyaImran)
- [Nauman](https://github.com/naumanzchaudhry)
