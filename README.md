# Booking App

## Overview

The Booking App is a comprehensive solution for users to book various services such as hotels, cars, cabs, flights, and taxis. Users can search and book services based on their preferences, including price range, dates, and locations. Built using the MERN stack (MongoDB, Express.js, React, Node.js), the app provides a seamless and efficient booking experience.

## Features

- **Hotel Booking**: Search and book hotels based on location, price range, and dates.
- **Car Rental**: Rent cars by selecting the desired dates and location.
- **Cab and Taxi Booking**: Book cabs and taxis for immediate or future use.
- **Flight Booking**: Find and book flights by specifying travel dates and destinations.
- **Search Functionality**: Users can filter their searches based on price range, dates, and location.
- **User Authentication**: Secure login and registration for users.
- **User Authorization**: Each user has a personal account with individual bookings.
- **Admin Access**: Admins can add or delete locations, cars, taxis, and flights, as well as manage prices and availability.
- **Responsive Design**: Optimized for desktop and mobile devices using simple CSS.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication & Authorization**: JWT (JSON Web Tokens)
- **Styling**: Simple CSS

## Project Structure

- **api**: Backend server (Node.js, Express.js)
- **client**: Frontend application for users (React.js)
- **admin**: Admin dashboard for managing bookings and services (React.js)

## Installation

### Prerequisites

- Node.js
- MongoDB

### Steps

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/booking-app.git
    cd booking-app
    ```

2. **Install dependencies**

    **Backend (API):**
    ```bash
    cd api
    npm install
    ```

    **Frontend (Client):**
    ```bash
    cd ../client
    npm install
    ```

    **Admin Dashboard:**
    ```bash
    cd ../admin
    npm install
    ```

3. **Set up environment variables**

    Create a `.env` file in the `api` directory and add the following variables:
    ```
    PORT=8800
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the application**

    **Backend (API):**
    ```bash
    cd api
    npm start
    ```

    **Frontend (Client):**
    ```bash
    cd ../client
    npm start
    ```

    **Admin Dashboard:**
    ```bash
    cd ../admin
    npm start
    ```

5. **Access the application**

    - User Client: Open your browser and navigate to `http://localhost:3000`.
    - Admin Dashboard: Open your browser and navigate to `http://localhost:3001`.

## Usage

1. Open your browser and navigate to `http://localhost:3000` for the user client.
2. Register or log in to your account.
3. Use the search functionality to find and book hotels, cars, cabs, flights, or taxis.
4. Follow the prompts to complete your booking.
5. Admins can log in to `http://localhost:3001` to manage locations, cars, taxis, flights, and bookings.

## Admin Functionality

- Admins can log in with their credentials to access the admin panel.
- Admins can add new locations, cars, taxis, and flights.
- Admins can update the count and price range of the available services.
- Admins can delete locations, cars, taxis, and flights as needed.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the project's style guidelines and includes appropriate tests.

Feel free to customize the content as needed to fit your project's specifics.

## Contact

For any questions or suggestions, feel free to open an issue or contact me at [ram.goyal.ug21@nsut.ac.in](mailto:ram.goyal.ug21@nsut.ac.in).
