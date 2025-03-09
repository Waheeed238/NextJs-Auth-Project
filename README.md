# Auth Next.js Project

This is a Next.js project for user authentication, including signup, login, logout, and email verification functionalities.

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

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

## Environment Variables

Create a `.env` file in the root of your project and add the following environment variables:

```env
MONGO_URL=your_mongodb_connection_string
TOKEN_SECRET=your_jwt_secret
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- Next.js Documentation - learn about Next.js features and API.
- Learn Next.js - an interactive Next.js tutorial.

You can check out the Next.js GitHub repository - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the Vercel Platform from the creators of Next.js.

Check out our Next.js deployment documentation for more details.