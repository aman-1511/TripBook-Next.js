# TripBook

## Overview

TripBook is a fully responsive travel booking web application built with Next.js that allows users to book hotels, flights, and car rentals. Users can filter and sort hotels by price, rating, and reviews to find the perfect accommodation for their travels.



<p align="center">
  <img src="https://img.shields.io/badge/Next.Js-3bc7bd?logo=next.js&style=for-the-badge&logoColor=black" alt="next-js" />
  <img src="https://img.shields.io/badge/Chakra%20UI-3bc7bd?style=for-the-badge&logo=chakraui&logoColor=white" alt="chakra-ui" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" />
  <img src="https://img.shields.io/badge/json%20web%20tokens-323330?style=for-the-badge&logo=json-web-tokens&logoColor=pink" alt="jwt" />
</p>



## Features

- 🔐 User authentication (Login and Signup)
- 🏨 Hotel booking with filtering and sorting options
- ✈️ Flight booking
- 🚗 Car rental services
- 💳 Secure checkout process
- 📱 Fully responsive design

## Screenshots

<table>
  <tr>
    <td><img src="https://i.ibb.co/Twq7Dq5/Screenshot-11.png" alt="Home Page" /></td>
    <td><img src="https://i.ibb.co/wYWWLG7/Screenshot-12.png" alt="Hotels Page" /></td>
  </tr>
  <tr>
    <td><img src="https://i.ibb.co/m5qtdsg/Screenshot-13.png" alt="Flight Booking" /></td>
    <td><img src="https://i.ibb.co/SdfCr02/Screenshot-14.png" alt="Car Rental" /></td>
  </tr>
  <tr>
    <td><img src="https://i.ibb.co/gRLr7Nw/Screenshot-15.png" alt="Hotel Details" /></td>
    <td><img src="https://i.ibb.co/HGrd1NT/Screenshot-16.png" alt="User Authentication" /></td>
  </tr>
  <tr>
    <td><img src="https://i.ibb.co/6XsMDY7/Screenshot-17.png" alt="Checkout Process" /></td>
    <td><img src="https://i.ibb.co/74bBb7Z/Screenshot-18.png" alt="Payment Options" /></td>
  </tr>
</table>

## Technology Stack

- **Frontend**: Next.js, Chakra UI
- **Backend**: Next.js API Routes
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

## Getting Started

### Prerequisites

- Node.js (14.x or higher)
- npm or yarn
- MongoDB connection

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/TripBook.git
   cd TripBook
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables
   Create a `.env.local` file in the root directory with your MongoDB connection string and JWT secret:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Run the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run ESLint to check code quality

## Deployment

The application can be deployed to platforms like Vercel or Netlify with minimal configuration.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.





