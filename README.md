**Waiter** is a Next.js application designed to simplify online ordering for restaurants. Customers can browse menus, place orders, and complete payments online, while restaurants can manage orders in real-time. The app is built with Next.js for fast server-side rendering, MongoDB for database management, and Tailwind CSS for a modern, responsive interface. It is deployed on Vercel, ensuring smooth performance and scalability.


**Features**

- Menu Browsing: Customers can explore restaurant menus with ease.

- Order Placement: Simple and intuitive online order process.

- Payment Integration: Secure payments through popular payment gateways.

- Admin Dashboard:
>  Product Creation: Admins can easily create and update menu items.
>  Sales Analytics: View sales data filtered by custom time durations (daily, weekly, monthly, etc.).

- Real-time Order Management: Track and manage customer orders in real-time.

- Responsive Design: Tailwind CSS ensures the app works on any device.


**Tech Stack**

- Framework: Next.js (React-based framework)

- Database: MongoDB (NoSQL database)

- Styling: Tailwind CSS (Utility-first CSS framework)

- Deployment: Vercel (Hosting and serverless functions)


**Installation and Setup**

- Clone the Repository:
git clone https://github.com/yourusername/waiter.git
cd waiter

- Install Dependencies:
npm install

- Set Up Environment Variables: Create a .env.local file in the root directory with the following environment variables:
MONGODB_URI=your_mongodb_connection_string
NEXT_PUBLIC_STRIPE_API_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key

- Run Development Server:
npm run dev
The app will be accessible at http://localhost:3000.

- Deploy on Vercel: Connect your repository to Vercel and follow their deployment instructions for seamless hosting and deployment.

**Project Structure**

├── components       --- Reusable React components

├── pages            --- Next.js pages and API routes

├── styles           --- Tailwind CSS configuration and global styles

├── lib              --- Utility functions and MongoDB connection

├── public           --- Static assets

├── .env.local       --- Environment variables (local setup)

└── README.md        --- Project documentation



**Usage**

For Customers: Browse restaurant menus, select items, place orders, and make payments online.
For Restaurants: View and manage orders, analyze sale for individual products and sections based on duration in real-time via the admin interface.
Deployment on [Vercel](https://vercel.com/)
To deploy the app to Vercel, follow these steps:

**Sign in to Vercel.**

Import your Waiter repository into a new project.
Set up your environment variables within Vercel’s project settings.
Deploy the app, and Vercel will automatically handle builds, server-side functions, and deployment.

**License**

This project is licensed under the MIT License. You are free to fork, modify, and distribute the code.

Waiter – Redefining the restaurant experience by making online ordering effortless.
