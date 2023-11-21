# Job Finder MERN Web Application

## Overview

The Job Finder MERN Web Application is a full-stack web application built using the MERN stack. It is designed to help users search for job opportunities based on their preferences and qualifications.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Allows users and companies to create accounts, log in, and manage their profiles.
- **Job Search**: Enables users to search for job opportunities based on various criteria such as location, job title, and skills.
- **Saved Jobs**: Users can save interesting job listings for future reference.
- **Job Posting**: Employers can post job opportunities, including details such as job title, description, and qualifications.
- **Responsive Design**: The application is designed to work seamlessly across various devices and screen sizes.

## Technologies Used

- **Frontend**:
  - React.js
  - Redux (for state management)
  - Axios (for API requests)
  - Tailwind CSS (for styling)

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (Atlas) - Database
  - Mongoose - ODM for MongoDB
  - JWT (JSON Web Tokens) for authentication

## Getting Started

To get started with the Job Finder MERN Web Application, follow these steps:

### Prerequisites

- Node.js installed on your machine
- MongoDB Atlas account for database storage

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/job-finder-mern.git
   ```

2. Navigate to the project directory:

   ```bash
   cd job-finder-mern
   ```

3. Install dependencies for the server:

   ```bash
   cd server
   npm install
   ```

4. Install dependencies for the client:

   ```bash
   cd ../client
   npm install
   ```

5. Create a `.env` file in the `server` directory and add the necessary environment variables:

   ```env
   PORT=5000
   MONGODB_URI=<your-mongodb-uri>
   JWT_SECRET=<your-jwt-secret>
   ```

### Usage

1. Start the server:

   ```bash
   cd ../server
   npm start
   ```

2. Start the client:

   ```bash
   cd ../client
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to access the Job Finder MERN Web Application.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License 
