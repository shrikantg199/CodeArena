# LeetCode Clone

This project is a clone of the popular coding interview preparation platform LeetCode. It allows users to solve coding problems, submit solutions, and track their progress.

## Features

- User authentication: Users can sign up, log in, and log out securely.
- Problem solving: Users can browse coding problems, submit solutions, and view their submissions.
- Leaderboard: Users can see their ranking on a global leaderboard based on their solved problems.

## Technologies Used

- Frontend:
  - React.js
  - Redux for state management
  - React Router for routing
  - Axios for making HTTP requests
  - Tailwind css

- Backend:
  - Express.js
  - MongoDB or any other database of choice (for storing user data, problems, and submissions)
  - JWT for user authentication and authorization
  - Mongoose for MongoDB object modeling

## Setup Instructions

1. **Clone the repository**:

    ```bash
    git clone https://github.com/shrikantg199/CodeArena
    cd lCodeArena
    ```

2. **Install dependencies**:

    ```bash
    # Install frontend dependencies
    cd frontend
    npm install

    # Install backend dependencies
    cd ../backend
    npm install
    ```

3. **Set up environment variables**:

    - Create a `.env` file in the `backend` directory.
    - Define environment variables such as `PORT`, `MONGODB_URI`, and `JWT_SECRET` in the `.env` file.

4. **Run the application**:

    ```bash
    # Start the backend server (from the backend directory)
    npm start

    # Start the frontend development server (from the frontend directory)
    npm run dev
    
    ```

5. **Access the application**:

    Open your web browser and navigate to `http://localhost:3000` to access the LeetCode clone application.
