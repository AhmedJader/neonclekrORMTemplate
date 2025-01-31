# Project Overview

This is a template repository for building applications using a simple Neon PostgreSQL database, Drizzle ORM, Clerk authentication, and Next.js framework.

## Technologies Used

- **Neon PostgreSQL**: A scalable, cloud-based PostgreSQL database.
- **Drizzle ORM**: A lightweight ORM for TypeScript and JavaScript, providing seamless database interaction.
- **Clerk**: A user authentication and management solution integrated with Next.js.
- **Next.js**: A React-based framework for building fast and user-friendly web applications.

## Project Structure

- **app/**: Contains the main application components and pages.
- **db/**: Includes database configuration and schema definitions using Drizzle ORM.
- **api/**: Holds API route handlers for server-side operations.
- **comp/**: Reusable React components.
- **pages/**: Next.js pages for routing.
- **styles/**: Global styles and Tailwind CSS configuration.
- **middleware.ts**: Custom middleware for authentication using Clerk.
- **next.config.ts**: Next.js configuration file.
- **tailwind.config.ts**: Tailwind CSS configuration file.

## Authentication

This template uses Clerk for user authentication and management. Ensure your Clerk API keys are set in the environment variables.

## Contributing

Feel free to open issues or submit pull requests to improve the template.