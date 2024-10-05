# Project Title: Two-Tier Web Application with Docker

This repository contains a two-tier web application consisting of a frontend built with React and a backend API built with Node.js, both containerized using Docker.

## Overview

The application is structured as follows:

- **Frontend**: A React application that serves as the user interface. It communicates with the backend API to display data and perform actions.
- **Backend**: A Node.js application that handles API requests, interacts with the database, and serves the frontend with the necessary data.

Both components are designed to be easily deployed and scaled in containerized environments.

## Technologies Used

- **Frontend**: React
- **Backend**: Node.js, Express
- **Containerization**: Docker

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Docker installed on your machine
- Docker Compose (optional for easier management)

### Clone the repository

```bash
git clone https://github.com/yourusername/my-two-tier-app.git
cd my-two-tier-app
```

### Build and Run the Docker Containers

1. Navigate to the project directory:
   ```bash
   cd my-two-tier-app
   ```

2. Build the Docker images:
   ```bash
   docker-compose build
   ```

3. Run the containers:
   ```bash
   docker-compose up
   ```

### Access the Application

- **Frontend**: Open your browser and go to `http://localhost:3000` (or the port you configured).
- **Backend**: The backend API will be accessible at `http://localhost:5000` (or the port you configured).

## Environment Variables

You can set the following environment variables in your `.env` file:

- `REACT_APP_API_URL`: The URL for the backend API, e.g., `http://backend:5000`.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Docker Documentation](https://docs.docker.com/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Node.js Documentation](https://nodejs.org/en/docs/)



