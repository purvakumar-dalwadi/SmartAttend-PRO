# SmartAttend-PRO

A comprehensive attendance management system with React frontend and Node.js backend.

## Project Structure

```

├── client/                     # React Frontend
│   ├── public/                # Static files
│   ├── src/                   # Source files
│   │   ├── components/        # Reusable UI components
│   │   ├── pages/             # Page components
│   │   ├── hooks/             # Custom React hooks
│   │   ├── utils/             # Utility functions
│   │   ├── context/           # React Context
│   │   ├── services/          # API calls
│   │   └── assets/            # Static assets
│   ├── package.json
│   └── vite.config.js
├── server/                    # Node.js Backend
│   ├── controllers/          # Route handlers
│   ├── models/               # MongoDB schemas
│   ├── routes/              # API routes
│   ├── middleware/          # Custom middleware
│   ├── utils/               # Helper functions
│   ├── config/              # Configuration files
│   └── server.js
└── shared/                  # Shared utilities
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher) or yarn
- MongoDB

### Installation

1. Clone the repository
2. Install dependencies for both client and server:
   ```
   cd client && npm install
   cd ../server && npm install
   ```

### Running the Application

1. Start the backend server:
   ```
   cd server
   npm start
   ```

2. Start the frontend development server:
   ```
   cd client
   npm run dev
   ```

## Environment Variables

Create a `.env` file in the server directory with the following variables:
```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

## License

This project is licensed under the MIT License.
