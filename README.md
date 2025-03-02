# Visited Countries Tracker

This is a Node.js application using Express and PostgreSQL that allows users to track the countries they have visited. The app supports multiple users, each with their own list of visited countries.

## Features
- Add and manage users.
- Track visited countries per user.
- Store data in a PostgreSQL database.
- Dynamic UI rendering with EJS.

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/visited-countries-tracker.git
   ```
2. Navigate to the project directory:
   ```sh
   cd visited-countries-tracker
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Set up a `.env` file with the following variables:
   ```env
   DB_USER=your_database_user
   DB_HOST=your_database_host
   DB_NAME=your_database_name
   DB_PASSWORD=your_database_password
   DB_PORT=your_database_port
   ```

## Usage
1. Start the PostgreSQL database and ensure the required tables (`users`, `countries`, `visited_countries`) exist.
2. Run the server:
   ```sh
   npm start
   ```
3. Open a browser and visit:
   ```
   http://localhost:3000
   ```

## Technologies Used
- Node.js
- Express.js
- PostgreSQL
- EJS (Embedded JavaScript Templates)
- dotenv (for environment variables)
