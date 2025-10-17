# MERN Ecommerce Application

<code>Currently under construction for additional features</code>

# Description

Full-stack ecommerce application built with MERN stack. This project has two features:

1. Buyers register and browse the marketplace while interacting with products across different categories.
2. Admins control and manage the marketplace items and customer acounts.

# Getting Started

## Dependencies

- Nodejs - The runtime environment of the application
- Reactjs - Component based UI library
- MongoDB - NoSQL database
- Expressjs - Framework to handle routes and requests
- Mongoose - MongoDB object modeling tool to model the database schema

## Installation and Running

Follow these steps to get the application running on your local machine.

### 1. Clone the Repository

```bash
git clone <repository-url>
cd mern-ecommerce
```

### 2. Install Dependencies

You'll need to install dependencies for the server and the client separately.

- **Root and Server Dependencies:**
  ```bash
  npm install
  cd server
  npm install
  cd ..
  ```

- **Client Dependencies:**
  ```bash
  cd client
  npm install
  cd ..
  ```

### 3. Set Up Environment Variables

- Go to the [MongoDB website](https://www.mongodb.com/), create a database, and get your connection string (URI).
- In the `server` directory, create a file named `.env`.
- Add your MongoDB URI to the `.env` file as shown below:

  ```
  MONGO_URI=your_mongodb_connection_string_here
  ```

### 4. Run the Application

Open two separate terminals to run the backend server and the frontend client simultaneously.

- **Terminal 1: Start the Server**
  ```bash
  cd server
  npm run dev
  ```

- **Terminal 2: Start the Client**
  ```bash
  cd client
  npm start
  ```

Your browser should open automatically to `http://localhost:3000`. The server will be running on `http://localhost:5000`.

# Languages and tools

- [Node](https://nodejs.org)
- [React](https://reactjs.org/)
- [Expressjs](https://expressjs.com)
- [Mongoose](https://mongoosejs.com)
- [Material UI](https://mui.com/)
