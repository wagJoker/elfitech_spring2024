# elfitech_spring2024
## Description:

This project is a full-stack web application built using React.js, Node.js, Express.js, and PostgreSQL. It utilizes Docker containers for development and deployment.

## Technologies Used:

Front-end: React.js
Back-end: Node.js, Express.js
Database: PostgreSQL
Containerization: Docker
_Getting Started:_

### 1. Prerequisites:

Ensure Docker is installed and running on your system.
### 2. Clone the Repository:

Clone this repository to your local machine using Git:

Bash
git clone [repository_url]

content_copy
### 3. Start the Docker Containers:

Navigate to the project directory and run the following command to start the Docker containers:

Bash
docker-compose up -d

content_copy
This will start the PostgreSQL database container and the Node.js application container.

### 4. Run Database Migrations (Optional):

If you haven't already created the database tables, you can run the database migrations using the following command:

Bash
node migrations/createEventsTable.js

content_copy
This will create the necessary tables in the PostgreSQL database.

### 5. Start the React Application:

Once the Docker containers are up and running, you can start the React application using the following command:

Bash
npm start

content_copy
This will start a development server and open the React application in your web browser.

__Additional Notes:__

For detailed development instructions, refer to the project's source code and documentation.
Make sure to replace [repository_url] with the actual URL of your project's repository.
Project Structure:

client: React.js front-end application
server: Node.js and Express.js back-end application
migrations: Database migration scripts
docker-compose.yml: Docker configuration file
Deployment:

The project can be deployed using Docker containers to various cloud platforms or on-premise servers. Refer to Docker documentation for specific deployment instructions.

__Contributing:__

Contributions to this project are welcome. Please follow the project's contribution guidelines for submitting pull requests.

_License:_

This project is licensed under the MIT License.
