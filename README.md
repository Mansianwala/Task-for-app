# Task-for-app
Real Time Messaging App

# ChatWave: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher (2023)

**Name: Mansi Choudhary**
**University: IIT Jodhpur**
**Department: Electircal Enginnering **

This is a repository for a Real-Time Messenger Called ChatWave: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher.

Key Features:

- Real-time messaging using Pusher
- Message notifications and alerts
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with NextAuth
- Google authentication integration
- Github authentication integration
- File and image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Message read receipts
- Online/offline user status
- Group chats and one-on-one messaging
- Message attachments and file sharing
- User profile customization and settings
- How to write POST, GET, and DELETE routes in route handlers (app/api)
- How to fetch data in server React components by directly accessing the database (WITHOUT API! like Magic!)
- Handling relations between Server and Child components in a real-time environment
- Creating and managing chat rooms and channels



### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
clone https://github.com/Mansianwala/Task-for-app.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=<your-database-url>
NEXTAUTH_SECRET=<your-nextauth-secret>

NEXT_PUBLIC_PUSHER_APP_KEY=<your-pusher-app-key>
PUSHER_APP_ID=<your-pusher-app-id>
PUSHER_SECRET=<your-pusher-secret>

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>

GITHUB_ID=<your-github-client-id>
GITHUB_SECRET=<your-github-client-secret>

GOOGLE_CLIENT_ID=<your-google-client-id>
GOOGLE_CLIENT_SECRET=<your-google-client-secret>

```

### Setup Prisma

```shell
npx prisma db push
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
