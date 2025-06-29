# Material Rental Application Backend

This is the backend for the Material Rental Application, built using Node.js, Express, and MongoDB. The backend provides RESTful APIs for managing materials, rental requests, and user authentication.

## Features

- **Material Management**: Admins can add, update, and delete materials.
- **Rental Management**: Users can request rentals for materials, and admins can approve or reject these requests.
- **User Authentication**: Secure access for users and admins with role-based permissions.
- **QR Code Integration**: Each material has a unique QR code for easy identification.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- Swagger for API documentation

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- MongoDB (local or cloud instance)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd material-rental-app/backend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Configure the database connection in `src/config/db.js`.

4. Start the server:
   ```
   npm start
   ```

### API Documentation

API endpoints are documented using Swagger. You can access the documentation at `http://localhost:3000/api-docs` after starting the server.

### Folder Structure

- **src**: Contains the main application code.
  - **controllers**: Logic for handling requests.
  - **models**: Mongoose schemas for MongoDB.
  - **routes**: API route definitions.
  - **middlewares**: Authentication and authorization middleware.
  - **config**: Configuration files, including database connection.
- **swagger**: Contains the Swagger YAML file for API documentation.
- **package.json**: Lists dependencies and scripts for the backend.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.#   r e n t A p p - w i t h - n o d e j s - a n d - e x p r e s s -  
 #   A s s e t  
 