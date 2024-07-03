
# RapidChat

RapidChat is a real-time chat application built with Node.js, Express, and React. This README provides the steps to set up and run the application locally.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:
- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Rakshit1110/RapidChat.git
   cd rapidchat
   ```

2. Set up the server configuration:

   - Rename the file `.env.sample` in the `server` folder to `.env`.
   - Update the `MONGO_URL` field in the `.env` file with the URL of your MongoDB database.

### Running the Server

1. Open the `RapidChat` folder in your terminal:

   ```bash
   cd server
   ```

2. Initialize npm and install the necessary packages:

   ```bash
   npm init -y
   npm i bcrypt cors dotenv express mongoose nodemon socket.io
   ```

3. Start the server:

   ```bash
   npm start
   ```

### Running the Client

1. Open a new terminal and navigate to the `public` folder:

   ```bash
   cd public
   ```

2. Install the required packages:

   ```bash
   npm i react-toastify socket.io-client styled-components uuid web-vitals
   ```

3. Start the client:

   ```bash
   npm start
   ```

### Demo

Demo pictures of the website are provided in the `Demo` folder.
