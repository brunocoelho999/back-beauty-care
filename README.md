# MVP Bruno Beauty Care - Female Aesthetic Care Platform

## Project Description

Bruno Beauty Care is a project focused on providing services and aesthetic care for women. Developed as part of our commitment to excellence in the beauty world, the application offers a comprehensive platform to explore, register, and manage various aesthetic care services.

## Key Features

### User Registration and Login

The application features a registration and login system that allows users to manage their accounts securely and personalized.

### Aesthetic Care List

Users can explore the complete list of aesthetic care available at Bruno Beauty Care, providing a detailed overview of each service.

### Administrator Functionalities

Administrators enjoy exclusive privileges, including the ability to:

- Create new aesthetic care services.
- Modify information for existing care services.
- Remove services from the platform.

### Aesthetic Care Details

Both types of users can access specific details of each aesthetic care, including its features and requirements. A filter has been implemented to facilitate searching based on user preferences.

## Technologies Used

**MERN Stack:**

- MongoDB with Mongoose (Backend)
- Express (Backend)
- React (Frontend)
- Node (Backend)

### Testing

All functionalities have been rigorously tested with Jest to ensure optimal performance.

## Endpoint Listing

### Users

| Method | URL             | Description                                                                   |
| ------ | --------------- | ----------------------------------------------------------------------------- |
| POST   | /users/register | Register a new user with mandatory fields.                                    |
| POST   | /users/login    | Authenticate a user with a username or email and password.                    |

### Aesthetic Care

| Method | URL                | Description                                                               |
| ------ | ------------------ | ------------------------------------------------------------------------- |
| GET    | /cares             | Get the list of available aesthetic care.                                  |
| GET    | /cares/search/type | Paginated by service types.                                               |
| POST   | /cares             | Add a new aesthetic care to the collection. Requires administrator rights.|
| PATCH  | /cares/:id         | Update details of an existing aesthetic care. Requires administrator rights.|
| DELETE | /cares/delete/:id  | Delete an aesthetic care from the collection. Requires administrator rights.|

## Execution Instructions

Before running the backend of the application, make sure to have the following dependencies installed:

1. **Node.js:** Download and install Node.js.
2. **MongoDB:** Download and install MongoDB.

### Backend Configuration

1. **Clone the repository:**

```bash
git clone https://github.com/brunocoelho999/back-beauty-care
