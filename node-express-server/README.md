Developed by: Rachita

The **Full Stack CRUD Application** is a web application built using **Angular, Node.js, Express.js, and MongoDB**.

The application allows users to manage tutorial information through a simple and responsive interface. Users can **add, view, update, delete, and search** records.

- **Frontend:** Angular 15
- **Backend:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB
- **ODM:** Mongoose
- **API:** REST API
- **Tools:** Git, GitHub, VS Code

- Create new tutorial records
- View existing records
- Update tutorial information
- Delete records
- Search tutorials by title
- Frontend and backend API integration
- MongoDB database connectivity
- Responsive user interface

As part of this project, I:

- Set up the Angular frontend.
- Developed the Node.js and Express.js backend.
- Connected the application to MongoDB using Mongoose.
- Implemented REST APIs for CRUD operations.
- Connected Angular services with the backend using HTTPClient.
- Implemented create, read, update and delete functionality.
- Added search functionality.
- Tested the frontend, backend, and database connection locally.
- Organized the project into separate frontend and backend directories.

Full Stack CRUD Application
│
├── angular-15-client/
│ ├── src/
│ ├── package.json
│ └── ...
│
└── node-express-server/
├── server.js
├── app/
├── package.json
└── ...

````

## How to Run the Project

### 1. Start the Backend

Open a terminal and run:

cd node-express-server
npm install
node server.js


The backend runs on:


http://localhost:8080


### 2. Start the Frontend

Open a **second terminal** and run:


cd angular-15-client
npm install
ng serve --port 8081


Open the application in your browser:

```text
http://localhost:8081
````

The application uses **MongoDB** to store tutorial records.

The backend connects to MongoDB and provides REST APIs that allow the Angular frontend to perform CRUD operations.

Through this project, I gained practical experience in:

- Full-stack web development
- Angular development
- Node.js and Express.js
- MongoDB and Mongoose
- REST API development
- CRUD operations
- Frontend-backend integration
- Database connectivity
- Git and project structure
