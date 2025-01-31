# Crypto Tracker

This is a simple private user crypto tracker application where users can track a single cryptocurrency of their choice. The application provides an easy way for users to monitor their selected crypto's price and receive updates at regular intervals. 

## Features

- **Single Crypto Tracking**: Users can select one cryptocurrency to track. This allows for personalized and focused monitoring of their asset.

- **Hourly Updates**: The application logs the price information of the selected cryptocurrency every hour. Users can also customize the logging frequency based on their preference.

- **Data Storage**: All cryptocurrency price data is logged to a Neon PostgreSQL serverless database using Drizzle ORM. This ensures efficient and scalable data management.

- **Authentication and User Management**: The application uses Clerk for user authentication and management. This provides a secure and seamless experience for user sign-in and registration.

## Technology Stack

- **Database**: Neon PostgreSQL serverless
- **ORM**: Drizzle ORM
- **Authentication**: Clerk
- **Frontend**: Built with Next.js and React

## Getting Started

To get started with the crypto tracker, you need to:

1. **Set up the environment**: Ensure you have the necessary environment variables set up, including the `DATABASE_URL` for your Neon PostgreSQL connection.

2. **Install dependencies**: Use the package manager of your choice to install the necessary dependencies listed in `package.json`.

3. **Run the application**: Start the application using the development server, and you can begin tracking your chosen cryptocurrency.

This application is ideal for users who want a simple yet effective solution for keeping tabs on their crypto investments without the complexity of managing multiple assets. Happy tracking!

