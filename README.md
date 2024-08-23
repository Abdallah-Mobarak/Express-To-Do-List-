# Express To-Do List 📝

This is a simple yet powerful backend project for managing a To-Do List, built with **Express.js**, **MongoDB**, **Mongoose**, and **Docker**.

## Features 🚀

- **Express.js**: Handles HTTP requests and routing with ease.
- **MongoDB**: A NoSQL database for flexible and scalable data storage.
- **Mongoose**: Simplifies data modeling and interaction with MongoDB.
- **Docker**: Containerizes the application and MongoDB for consistent and efficient deployment across different environments.

## Prerequisites 📋

- **Node.js** (v14.x or higher)
- **Docker** and **Docker Compose**
- **MongoDB** (or run using Docker)

## Installation and Setup 🛠

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Abdallah-Mobarak/Express-To-Do-List-.git
   cd express-to-do-list

2. **Install dependencies**:
   ```bash
   npm install 

3. **Run MongoDB with Docker**:
If you have Docker installed, you can easily spin up MongoDB using Docker Compose:
   ```bash
   docker-compose up -d
 ```


 4. **Run the application**:
    ```bash
    npm start
The application will be running on http://localhost:3000.

## Usage 🎯

This API allows you to:

- **Create** new to-do items
- **Read** all to-do items
- **Update** existing to-do items
- **Delete** to-do items

Explore the API using tools like [Postman](https://www.postman.com/) or [cURL](https://curl.se/).
## Project Structure 📂

- `app.js`: The main entry point for the application.
- `routes/`: Contains all route definitions.
- `models/`: Mongoose schemas and models for MongoDB.
- `controllers/`: Handles the logic for each route.

## Docker Setup 🐳

If you prefer using Docker, this project includes a `docker-compose.yml` file that sets up both the application and MongoDB:

- **MongoDB**: Configured with a persistent volume for data storage.
- **App**: Express.js server running in a Docker container.

To build and run the containers:

```bash
docker-compose up --build
```
## Contributing 🤝
Feel free to fork this repository, make your changes, and submit a pull request. All contributions are welcome!
