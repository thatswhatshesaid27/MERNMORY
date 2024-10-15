
# Mernmory

**Mernmory** is a full-stack social media application that allows users to share their personal events and experiences. Built using the **MERN stack**, it delivers a dynamic and scalable platform for users to connect and share posts.

## Features

- **User Posts**: 
  - Users can create, view, and share personal posts with others on the platform.
  
- **API-Driven Backend**:
  - The back-end is built using **Express.js** and **Node.js**, handling all API requests and server-side logic for seamless communication between the client and server.
  
- **Front-end Development**:
  - The application uses **React** for building the interactive user interface.
  - **Redux** is utilized for managing global state, ensuring smooth transitions and data flow throughout the app.
  
- **Database**:
  - **MongoDB** is used for scalable and flexible data storage, allowing for efficient handling of user data and posts.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: [Download Node.js](https://nodejs.org/en/)
- **MongoDB**: Ensure MongoDB is installed and running locally or use MongoDB Atlas.

.
├── client               # React front-end
│   ├── public           # Public assets
│   └── src              # Source files
│       └── components   # React components
│       └── redux        # Redux store setup
├── server               # Express back-end
│   ├── controllers      # Request handlers
│   ├── models           # MongoDB schemas
│   ├── routes           # API routes
├── package.json         # Project configurations
└── .gitignore           # Ignored files and directories


### Installation & Execution

 **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/mernmory.git
   cd client
   npm install
   cd ../server
   npm install
   npm run start - Client
   npm run start - Server






