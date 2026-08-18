# Full Stack CRUD Application

**Author:** Rachita R.

A full-stack CRUD application developed using **Angular, Node.js, Express.js, and MongoDB**. The application provides a responsive interface for managing tutorial records with authentication and complete Create, Read, Update, and Delete functionality.

This project was developed as part of the **AI Full Stack Developer Intern technical assignment for Binaried**.

---

## 🚀 Features

* Basic authentication/login
* Create tutorial records
* View tutorial records
* Update tutorial records
* Delete tutorial records
* RESTful API using Node.js and Express.js
* MongoDB database integration
* Responsive Angular frontend
* Client-server communication using HTTP APIs
* Structured frontend and backend code
* Error handling and validation
* AI-assisted development workflow

---

## 🛠️ Technology Stack

### Frontend

* Angular
* HTML
* CSS
* TypeScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Development Tools

* Git
* GitHub
* Visual Studio Code
* Postman / API testing tools

### AI Tools

* ChatGPT
* Claude
* AI-assisted coding tools

---

# 📁 Project Structure

```text
FULL_STACK_CRUD_APPLICATION/
│
├── frontend/
│   └── Angular application
│
├── node-express-server/
│   ├── app/
│   │   ├── controllers/
│   │   ├── models/
│   │   └── routes/
│   │
│   ├── package.json
│   └── server.js
│
├── output/
│   └── project screenshots / output files
│
├── .gitignore
└── README.md
```

---

# ⚙️ Setup Instructions

## 1. Prerequisites

Make sure the following are installed:

* Node.js
* npm
* Angular CLI
* MongoDB / MongoDB Atlas
* Git

Check the installations:

```bash
node --version
npm --version
ng version
git --version
```

---

## 2. Clone the Repository

```bash
git clone https://github.com/rachitar29/FULL_STACK_CRUD_APPLICATION.git
```

Move into the project directory:

```bash
cd FULL_STACK_CRUD_APPLICATION
```

---

# 🔹 Backend Setup

Navigate to the backend:

```bash
cd node-express-server
```

Install dependencies:

```bash
npm install
```

Create a `.env` file in the backend directory.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

> Do not commit the `.env` file or expose database credentials publicly.

Start the backend:

```bash
npm start
```

The backend will run on the configured port, for example:

```text
http://localhost:5000
```

---

# 🔹 Frontend Setup

Open another terminal.

Navigate to the Angular application:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the Angular development server:

```bash
ng serve
```

Open the application in your browser:

```text
http://localhost:4200
```

---

# 🔐 Authentication

The application includes basic authentication to restrict access to the main application.

After successful login, the user can access the tutorial management interface and perform CRUD operations.

The authentication implementation is intentionally kept simple because the assignment permits basic or dummy authentication.

---

# 🔄 CRUD Operations

The application implements all four CRUD operations.

### Create

Users can add a new tutorial by entering the required information through the frontend form.

### Read

Existing tutorial records are retrieved from MongoDB through the backend API and displayed in the Angular application.

### Update

Users can edit existing tutorial records and save the updated information.

### Delete

Users can remove tutorial records through the delete functionality.

The Angular frontend communicates with the Node.js/Express backend through REST APIs, while the backend handles communication with MongoDB.

---

# 🤖 AI Tools Used

The following AI tools were used during development:

### ChatGPT

Used for:

* Understanding technical concepts
* Debugging errors
* Troubleshooting MongoDB connection issues
* Exploring implementation approaches
* Understanding Angular and Node.js errors
* Improving documentation
* Reviewing possible solutions

### Claude

Used for:

* Exploring alternative implementation approaches
* Understanding and reviewing code
* Debugging and improving development workflows

### AI-Assisted Coding

AI-assisted coding was used to improve development speed, generate suggestions, and explore implementation patterns.

AI was used as a development assistant rather than as a replacement for understanding the code.

---

# 🧠 Where AI Helped

AI assistance was mainly used in the following areas:

1. **Debugging**

   AI tools helped identify possible causes of errors during Angular, Node.js, and MongoDB integration.

2. **Code Understanding**

   AI was used to explain unfamiliar code, functions, API requests, and framework concepts.

3. **Implementation Suggestions**

   AI helped explore different approaches for implementing frontend components, backend routes, and CRUD functionality.

4. **Database Troubleshooting**

   AI assistance was useful while troubleshooting MongoDB connection configuration, environment variables, and backend connectivity.

5. **Documentation**

   AI helped organize and improve project documentation and README content.

6. **Code Improvement**

   AI suggestions were reviewed and modified where necessary to fit the application's requirements.

All AI-assisted code was reviewed, understood, tested, and adapted before being used in the application.

---

# 👩‍💻 What I Implemented Myself

I was responsible for integrating and implementing the complete application and ensuring that the different components worked together.

My implementation work included:

* Setting up the Angular frontend
* Setting up the Node.js and Express.js backend
* Connecting the application to MongoDB
* Implementing the CRUD functionality
* Creating and integrating REST APIs
* Connecting Angular services to backend APIs
* Implementing the authentication flow
* Handling frontend and backend integration
* Testing CRUD operations
* Debugging application and database issues
* Configuring the development environment
* Managing the project using Git and GitHub
* Testing the final application end-to-end
* Reviewing and adapting AI-generated suggestions according to project requirements

The final implementation was tested locally to verify that the frontend, backend, and database communicate correctly.

---

# 🧩 Challenges Faced

## 1. MongoDB Connection

One of the main challenges was establishing and troubleshooting the connection between the Node.js backend and MongoDB.

I had to verify:

* MongoDB connection configuration
* Connection string
* Environment variables
* Backend configuration
* Database accessibility

This helped me understand the importance of separating configuration from source code and debugging database connectivity systematically.

---

## 2. Frontend and Backend Integration

Another challenge was connecting the Angular frontend with the Express.js REST API.

I needed to ensure that:

* API endpoints were correct
* HTTP requests were properly handled
* Data was correctly sent from Angular
* Backend responses were correctly displayed
* CRUD operations remained synchronized with MongoDB

---

## 3. Debugging CRUD Operations

During development, individual CRUD operations required testing and debugging to make sure that changes made through the frontend were correctly reflected in the database.

Testing each operation separately helped identify issues more systematically.

---

## 4. Environment Configuration

Managing environment-specific configuration was another important part of the project.

Sensitive information such as MongoDB credentials should not be included directly in the source code, so environment variables were used for configuration.

---

# 📱 Responsive Design

The frontend was designed to provide a clean and usable interface across different screen sizes.

The application was tested using browser responsive development tools to ensure that the main functionality remains accessible on smaller screens.

---

# 📌 What I Learned

Through this project, I gained practical experience in:

* Building an Angular frontend
* Developing REST APIs with Node.js and Express.js
* Working with MongoDB
* Connecting frontend and backend applications
* Implementing CRUD operations
* Basic authentication
* Debugging full-stack applications
* Using Git and GitHub
* Using AI tools responsibly during software development
* Reviewing and validating AI-generated code
* Breaking technical problems into smaller debugging steps

Most importantly, I learned that AI tools are most useful when combined with a clear understanding of the problem and proper testing of the generated solution.

---

# 🔮 Future Improvements

If I had more time, I would improve the application with the following features:

### Authentication

* JWT-based authentication
* Password hashing
* Secure session management
* Role-based access control

### User Experience

* Advanced search
* Filtering and sorting
* Pagination
* Better form validation
* Improved loading and error states
* Toast notifications

### Backend

* More comprehensive API validation
* Centralized error handling
* API documentation
* Automated backend testing

### Database

* Improved database indexing
* More structured data validation
* Additional relationships between users and tutorials

### Deployment

* Deploy the Angular frontend
* Deploy the Node.js backend
* Connect the production application to MongoDB Atlas
* Configure production environment variables

### AI Features

* AI-powered tutorial recommendations
* Automatic tutorial categorization
* AI-generated tutorial summaries
* Intelligent search functionality

---

# 🧪 Testing

The following functionality was tested:

* Login/authentication
* Tutorial creation
* Tutorial retrieval
* Tutorial editing
* Tutorial deletion
* MongoDB persistence
* Frontend-backend API communication
* Page refresh and data persistence
* Responsive interface

---

# 📸 Project Screenshots

Screenshots demonstrating the application interface and functionality are included in the project repository.

---

# 🔗 Project Links

### GitHub Repository

https://github.com/rachitar29/FULL_STACK_CRUD_APPLICATION

### Application Demo

Add the demonstration video/live deployment link here.

---



# 📄 Assignment Context

This project was developed for the **AI Full Stack Developer Intern technical assignment at Binaried** using Angular, Node.js, MongoDB, and AI-assisted development tools.
