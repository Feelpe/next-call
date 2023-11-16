# Next Schedule

This web application allows user to sign in using their Google Account and create meetings on Google Meet via the application calendar. Built with Typescript, React.js, Next.js, Prisma, Zod, Nookies, Axios, Dayjs and Eslint.

## Getting Started

Before you start, ensure that you have these installed:

- Node.js
- Git

# Setting Up the Project

1. Clone the repository:

```
git clone https://github.com/Feelpe/next-schedule
```

2. Move to the project directory and install the project dependencies:

```
cd next-schedule
npm install
```

## Configuring Google OAuth

This application uses Google OAuth for authentication. Refer to the Google OAuth documentation on how to set it up, and afterwards, keep track of your Client ID and Client Secret.

## Configuring Google Calendar

The application integrates Google Calendar for scheduling meetings. Instructions on setting it up are available in the Google Calendar API documentation.

## Environment Variables

Create a .env.local file at the root of the project. Copy and paste the .env.example and fullfill the variables with your GOOGLE_CLIENT_ID, GOOGLE_CLIENT_SECRET, NEXTAUTH_SECRET (any secret digits just to api/auth work), and DATABASE_URL.

## Setup Prisma

Push the Prisma schema state to the database:

```
prisma db push
```

Run the application

```
npm run dev
```

Open your browser and go to http://localhost:3000.
Note: Replace 3000 if your app is running on a different port.
