# Auth Next.js Project

This is a Next.js project for user authentication, including signup, login, logout, and email verification functionalities.

## Project Overview

- **Purpose**: User authentication system.
- **Technologies**: Next.js, TypeScript, MongoDB, Tailwind CSS.

## Features

- User Signup
- User Login
- User Logout
- Email Verification
- User Profile Management

## Project Structure

- `.env`: Environment variables.
- `.gitignore`: Git ignore file.
- `.next/`: Next.js build output.
- `eslint.config.mjs`: ESLint configuration.
- `next-env.d.ts`: Next.js environment types.
- `next.config.ts`: Next.js configuration.
- `package.json`: Project dependencies and scripts.
- `postcss.config.mjs`: PostCSS configuration.
- `public/`: Public assets.
- `README.md`: Project documentation.
- `src/`: Source code.
  - `app/`: Application code.
    - `api/users/login/route.ts`: Handles user login.
    - `api/users/logout/route.ts`: Handles user logout.
    - `api/users/signup/route.ts`: Handles user signup.
    - `api/users/me/route.ts`: Retrieves user details.
    - `api/users/verifyemail/route.ts`: Handles email verification.
    - `globals.css`: Global CSS styles.
    - `layout.tsx`: Root layout component.
    - `page.tsx`: Home page component.
    - `signup/page.tsx`: Signup page component.
    - `login/page.tsx`: Login page component.
    - `profile/[id]/page.tsx`: User profile page component.
    - `profile/page.tsx`: Profile page component.
  - `dbConfig/`: Database configuration.
  - `helpers/`: Helper functions.
  - `middleware.ts`: Middleware configuration.
  - `models/`: Database models.
- `tailwind.config.ts`: Tailwind CSS configuration.
- `tsconfig.json`: TypeScript configuration.