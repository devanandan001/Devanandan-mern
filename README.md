# DevWise ECommerce

## Requirements

* Node.js
* npm
* Git

## Example `.env` 

* Add the `.env` file inside `backend/` and `frontend/`
```
PORT=3000
FRONTEND_URL=http://localhost:5173
MONGO_URI=mongodb+srv://user:pass@cluster.mongodb.net/

cloud_name=xxxxxxxxx
api_key=xxxxxxxxxxxxxx
api_secret=xxxxxxxxxxxxxx

JWT_USER_PASSWORD=user
JWT_ADMIN_PASSWORD=password

NODE_ENV=development
```

## Backend Setup

```sh
cd backend
npm install
npm start
```

## Frontend Setup

```sh
cd frontend
npm install
npm run dev
```

## Project Structure

### Backend

* `index.js`: Entry point for the backend server.
* `config.js`: Configuration settings for the backend (e.g., database connection, JWT secret).
* `controllers/`: Contains the logic for handling requests (e.g., user authentication, book management).
* `middlewares/`: Custom middleware (e.g., authentication checks, error handling).
* `models/`: Defines the schema for data models (e.g., User, Book, Order).
* `routes/`: Routes for various API endpoints.

### Frontend

* `src/`: Contains the React components and related frontend code.
* `src/admin/`: Admin panel
* `src/components/`: React components
* `public/`: Public assets like images, fonts, etc.

## Technologies Used

* Backend:
    * Node.js
    * Express.js
    * MongoDB (or other database solutions as per configuration)
    * JWT for authentication
* Frontend:
    * React
    * Vite (for fast build and hot-reloading)
    * Tailwind CSS (for utility-first styling)
    * ESLint (for code linting)

## Contributing

We welcome contributions! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Make your changes and commit them (git commit -m 'Add some feature').
4. Push your changes to the branch (git push origin feature/your-feature).
5. Open a Pull Request.

