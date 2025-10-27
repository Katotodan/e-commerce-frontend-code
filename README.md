# E-Commerce Frontend (React)

React-based client for the e-commerce project. Built with Create React App and communicates with the backend API for products and authentication.

## Prerequisites
- Node.js (v16+ recommended)
- npm

## Quick start (development)
1. Open a terminal and change into the frontend folder:

	cd e-commerce-frontend-code

2. Install dependencies:

	npm install

3. Create a `.env` file at the project root to configure the API URL used by the client. Example:

	REACT_APP_API_URL=http://localhost:8080

4. Start the development server:

	npm start

The app will open at http://localhost:3000 by default.

## API notes
The frontend currently attempts to communicate with the backend at the API URL you provide via `REACT_APP_API_URL` .

- `REACT_APP_API_URL` points to the backend (e.g. http://localhost:8080),

The backend seeks to authenticate users and provide advanced product searches.
The backend code can be found  [here](https://github.com/Katotodan/e-commerce-backend-code)


## Environment variables
- REACT_APP_API_URL — base URL for backend API (optional)

## Troubleshooting
- If the site loads but API requests fail: verify the backend is running and CORS/FRONTEND_URL are configured correctly on the server.

## Author
APIPAWE KATOTO Daniel

## License
MIT