# Spring WebSocket Chat App

A professional real-time one-to-one chat application built with Spring Boot, WebSocket, and MongoDB.

## Features

- Real-time messaging using WebSocket
- User management
- Chat rooms
- MongoDB for data persistence
- Responsive web interface

## Prerequisites

- Java 17
- Maven
- Docker (for local MongoDB)
- MongoDB Atlas (for production)

## Local Development

1. Clone the repository
2. Start MongoDB:
   ```bash
   docker-compose up -d
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
4. Open http://localhost:8080

## Deployment

This application is configured for deployment on Render.

### Setup MongoDB Atlas

1. Create a MongoDB Atlas account
2. Create a cluster and get the connection string
3. Set the `MONGODB_URI` environment variable in Render

### Deploy to Render

1. Connect your GitHub repository to Render
2. Use the `render.yaml` configuration
3. Set environment variables:
   - `MONGODB_URI`: Your MongoDB Atlas connection string
   - `PORT`: 8080

## CI/CD

GitHub Actions pipeline:
- Builds and tests on every push/PR
- Deploys to Render on main branch push

## API Endpoints

- WebSocket: `/ws`
- REST API: `/api/*`

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make changes
4. Submit a pull request

## License

MIT License

Provide step-by-step instructions on how to install and set up your project locally.

```bash
# Clone the repository
git clone https://github.com/iharsh3289/spring-websocket-chat-app

# Change into the project directory
cd your-project

# Build the project
./mvnw clean install
```

---
## Technologies

This project is mainly implement using the following technologies

- Websocket
- Spring Boot 3.x.x
- MongoDB
- Javascript
- HTML
- CSS

---

