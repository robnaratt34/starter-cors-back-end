# CORS Back-End Starter Project

This project serves as a foundation for handling Cross-Origin Resource Sharing (CORS) issues when building back-end applications. It demonstrates how to configure a Node.js server to allow or restrict access to external APIs from different origins.

## Features
- Configurable CORS settings
- Basic server setup for API requests

## Installation

1. Clone or fork this repository:
   ```bash
   git clone https://github.com/Thinkful-Ed/starter-cors-back-end.git
   ```
2. Navigate to the project directory:
   ```bash
   cd starter-cors-back-end
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   npm start
   ```

   To run in development mode (with auto-reload):
   ```bash
   npm run start:dev
   ```

5. Set the `PORT` environment variable if needed. The default is `5555`.

## Usage
The application starts a server on the specified port, allowing requests from different origins based on CORS configuration. This starter code helps with setting up an API backend that interacts with various front-end clients.

## Technologies
- **Node.js**: JavaScript runtime for building server-side applications.
- **Express**: Web framework for managing server routes and middleware.
- **CORS**: Configurable middleware for handling cross-origin requests.
