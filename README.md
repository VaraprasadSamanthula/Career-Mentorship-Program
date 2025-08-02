# Mentorship Portal Client

A React-based frontend for the mentorship portal application.

## Environment Setup

### Backend API Configuration

The application connects to the backend API through the `REACT_APP_API_URL` environment variable.

#### Development
For local development, the app will use `http://localhost:5000` as the default backend URL.

#### Production
For production deployment, set the environment variable to your backend URL:

```bash
REACT_APP_API_URL=https://edunet-final-project-dldw.onrender.com
```

### Environment Files

- `.env` - Contains the current environment variables (not committed to git)
- `.env.example` - Example environment file for reference

### Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Runs the test suite
- `npm eject` - Ejects from Create React App (irreversible)

## API Configuration

The application uses a centralized API configuration in `src/utils/api.js` that:

- Automatically handles authentication tokens
- Provides consistent error handling
- Supports both development and production environments
- Includes request/response interceptors

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Set up environment variables (see above)

3. Start the development server:
   ```bash
   npm start
   ```

The app will be available at `http://localhost:3000` 