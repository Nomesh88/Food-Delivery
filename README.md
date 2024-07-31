# Food Delivery App

## Description

A food delivery app built using the MERN stack (MongoDB, Express, React, Node.js) that allows users to browse through various restaurants, place orders, and track their deliveries. The app offers an intuitive interface for users to select and customize their meals, view real-time order status, and make secure payments.

## Features

- **User Authentication**: Sign up, log in, and manage user profiles.
- **Restaurant Listings**: Browse restaurants, view menus, and read reviews.
- **Order Placement**: Customize orders, add items to the cart, and checkout.
- **Real-time Order Tracking**: Track the status of your orders in real-time.
- **Payment Integration**: Secure payment processing using a popular payment gateway.
- **Admin Dashboard**: Manage restaurants, view orders, and update order statuses.

## Technologies Used

- **Frontend**: React, Redux, React Router, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Processing**: Stripe or PayPal (choose based on your implementation)
- **Real-time Updates**: Socket.io (for real-time order tracking)

## Installation

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Clone the Repository

```bash
git clone https://github.com/yourusername/food-delivery-app.git
cd food-delivery-app
```

### Frontend Setup

1. Navigate to the frontend directory:

    ```bash
    cd client
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

### Backend Setup

1. Navigate to the backend directory:

    ```bash
    cd server
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `server` directory with the following environment variables:

    ```bash
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key  # or PAYPAL_CLIENT_ID and PAYPAL_CLIENT_SECRET if using PayPal
    ```

4. Start the server:

    ```bash
    npm start
    ```

### Database Setup

1. Start MongoDB on your local machine or use a cloud-based MongoDB service.
2. Ensure the `MONGODB_URI` in the `.env` file is correctly configured to connect to your MongoDB instance.

## Usage

1. **User Registration**: Register a new account by visiting the signup page.
2. **Login**: Log in using your credentials.
3. **Browse Restaurants**: Explore available restaurants and their menus.
4. **Place Order**: Add items to your cart, customize your order, and proceed to checkout.
5. **Track Order**: View the status of your order in real-time.
6. **Admin**: Access the admin dashboard to manage restaurants and orders.

## Testing

To run tests, navigate to the `server` directory and execute:

```bash
npm test
```

## Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

