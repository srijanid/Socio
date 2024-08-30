# Social Media MERN App

![App Screenshot](./screenshot.png)

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

This is a complete Fullstack Responsive Social Media App built using the MERN (MongoDB, Express.js, React, Node.js) stack. The application allows users to create an account, log in, post updates, like posts, switch between light and dark mode, and more. The app is designed to be fully responsive and provides a seamless user experience across different devices.

## Features

- **User Authentication**: Sign up, log in, and log out securely using JWT-based authentication.
- **Responsive Design**: Mobile-first approach, ensuring the app looks great on any device.
- **Dark Mode**: Toggle between light and dark modes for a personalized experience.
- **User Profile**: View and edit your profile information.
- **Create Posts**: Share your thoughts with the community by creating new posts.
- **Like Posts**: Engage with posts by liking them.
- **Real-time Updates**: The feed updates in real-time as new posts are created.
- **MUI Integration**: Styled using Material-UI for a modern and cohesive look.

## Tech Stack

- **Frontend**: React, Material-UI (MUI)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Version Control**: Git & GitHub

## Installation

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB instance (local or cloud)

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/srijanid/Socio.git
    cd social-media-mern-app
    ```

2. Install backend dependencies:
    ```bash
    cd backend
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the `backend` directory.
    - Add the following variables:
      ```bash
      PORT=5000
      MONGO_URI=your_mongodb_connection_string
      JWT_SECRET=your_jwt_secret_key
      ```

4. Start the backend server:
    ```bash
    npm start
    ```

### Frontend Setup

1. Install frontend dependencies:
    ```bash
    cd ../frontend
    npm install
    ```

2. Set up environment variables:
    - Create a `.env` file in the `frontend` directory.
    - Add the following variables:
      ```bash
      REACT_APP_API_URL=http://localhost:5000
      ```

3. Start the frontend development server:
    ```bash
    npm start
    ```

## Usage

1. Navigate to `http://localhost:3000` in your web browser.
2. Create an account or log in with existing credentials.
3. Explore the app by creating posts, liking content, and toggling between light and dark modes.

## API Documentation

The API provides endpoints for user authentication, post management, and more. Below are some of the key endpoints:

- **POST /api/auth/register**: Register a new user.
- **POST /api/auth/login**: Log in a user and return a JWT token.
- **GET /api/posts**: Get all posts.
- **POST /api/posts**: Create a new post.
- **PUT /api/posts/:id/like**: Like a post.

## Screenshots

### Light Mode
![Light Mode](./screenshots/light_mode.png)

### Dark Mode
![Dark Mode](![image](https://github.com/user-attachments/assets/49436b5e-cca4-4626-bf63-d22e3fa6dfab)
)

### User Profile
![User Profile](./screenshots/user_profile.png)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

- **GitHub**: [srijanid](https://github.com/srijanid)
- **Email**: srijanidas06@gmail.com
