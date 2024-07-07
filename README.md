# Task Manager Application

This repository contains a Task Manager application built with the MERN stack (MongoDB, Express, React, Node.js). The application allows users to manage their tasks efficiently with features such as creating, updating, and deleting tasks.

## Features

- User Authentication (JWT)
- Task Management (Add/Update/Delete)
- Responsive UI with Tailwind CSS
- API calls with Axios

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14.x or higher)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Deepak931014/ProIndia-TaskManager-Assignment.git
    cd task-manager
    ```

2. Install dependencies for the backend:
    ```bash
    cd backend
    npm install
    ```

3. Install dependencies for the frontend:
    ```bash
    cd ../frontend
    npm install
    ```

## Configuration

1. Create a `.env` file in the `backend` directory with the following content:
    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

2. Update the API URL in the `frontend` configuration:
    - Open `frontend/src/config.js` (or wherever the API URL is set)
    - Ensure it points to your backend API, e.g.:
      ```javascript
      export const API_URL = 'http://localhost:5000/api';
      ```

## Running the Application

### Backend

1. Start the backend server:
    ```bash
    cd backend
    npm start
    ```

### Frontend

1. Start the frontend development server:
    ```bash
    cd frontend
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000` to see the application running.

## Deployment

To deploy the backend:

1. Ensure your backend code is deployed on a service like Vercel, Heroku, or any other platform that supports Node.js applications.

2. Update the frontend `API_URL` to point to your deployed backend.

To deploy the frontend:

1. Build the frontend for production:
    ```bash
    cd frontend
    npm run build
    ```

2. Deploy the `build` folder to a static site hosting service like Vercel, Netlify, or GitHub Pages.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests for any features, enhancements, or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, feel free to open an issue or reach out to me at [your-email@example.com](mailto:your-email@example.com).

---

Happy Coding!
