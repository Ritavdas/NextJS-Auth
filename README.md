# NextJS-Auth

A Next.js project that demonstrates the implementation of Google, GitHub, and custom credential login using the NextAuth.js library. This app provides a seamless authentication experience with a clean and responsive user interface.

![Home Page](./images/home_page.png)

## Features

-  Google, GitHub, and custom credential authentication
-  Responsive design
-  Clean and modern user interface
-  Proper form validation
-  Informative error handling

## Tech Stack

-  Next.js
-  NextAuth.js
-  React
-  Mongoose
-  Tailwind CSS

## Getting Started

1. Clone the repository

```
git clone https://github.com/Ritavdas/NextJS-Auth.git
```

2. Change the directory

```
   cd NextJS-Auth
```

3. Install the dependencies

```
npm install
```

4. Rename `.env.example` to `.env.local` and set up the environment variables

```
NEXTAUTH_URL=http://localhost:3000
MONGODB_URI=your_mongodb_uri
GOOGLE_ID=your_google_client_id
GOOGLE_SECRET=your_google_client_secret
GITHUB_ID=your_github_client_id
GITHUB_SECRET=your_github_client_secret
```

5. Start the development server

```
npm run dev
```

6. Open your browser and navigate to http://localhost:3000

## Screenshots

![Login Page](./images/login_page.png)
![Register Page](./images/register_page.png)
![User Page](./images/user_page.png)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
