
# Submission Management Backend Server

Welcome to the Submission Management Backend Server! This server facilitates seamless API calls from the frontend for saving and retrieving submissions. It is built with Express and TypeScript, providing a solid backend infrastructure for your application.

## Overview

The backend server is the core of your submission management system, offering three key endpoints: /ping, /submit, and /read, each serving specific functions to meet your application's needs.

### Endpoints

- **/ping (GET)**:
  Returns "True" to indicate that the server is operational.

- **/submit (POST)**:
  Handles new form submissions. Accepts parameters such as "name," "email," "phone," "github_link," and "stopwatch_time" in the request body.

- **/read (GET)**:
  Retrieves saved form submissions. Requires a query parameter "index" to read the (index+1)th form submission.

## Getting Started

To set up and run the backend server locally, follow these steps:

1. Clone the repository to your local machine.
2. Install Node.js if it is not already installed.
3. Navigate to the project directory in your terminal.
4. Run `npm install` to install the dependencies.
5. Create a JSON file named "db.json" to act as the database for storing submissions.
6. Run `npm start` to launch the server.

## Additional Features

The backend server covers essential functionalities, but you can expand its capabilities with features such as:

- **Deleting Submitted Forms**: Add functionality to delete specific form submissions.
- **Editing Submitted Forms**: Allow users to update or correct existing form entries.
- **Searching Forms by Email ID**: Implement a search function to retrieve submissions based on email IDs.

## Contributing

If you wish to contribute to the backend server's development, you are welcome to fork the repository and submit pull requests with enhancements or bug fixes. Your contributions are highly valued!

## License

This project is licensed under the MIT License, allowing for open collaboration and usage.