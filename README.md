# Kanban Board

## Overview

Kanban Board is a simple, interactive web application that implements the Kanban methodology to manage tasks and projects effectively. It allows users to create, view, update, and delete tasks across different project stages (e.g., To Do, In Progress, Done). This application is designed for both personal use and team collaboration to streamline task management in an easy-to-use interface.

## Features

- **Create Tasks**: Easily add new tasks to the board.
- **Drag and Drop**: Move tasks between columns (To Do, In Progress, Done).
- **Edit Tasks**: Modify task details as needed.
- **Delete Tasks**: Remove tasks from the board when no longer required.
- **Save Progress**: The board's current state is preserved, so you can continue working seamlessly.

## Technologies Used

- **Frontend**:
  - HTML
  - CSS
  - JavaScript
  - React (for building the user interface)
  
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (for database management)

- **Others**:
  - LocalStorage (for temporary storage on the client-side)

## Installation

Follow these steps to run the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/lakshyar24/Kanban-Board.git
   ```

2. **Navigate into the project folder**:
   ```bash
   cd Kanban-Board
   ```

3. **Install dependencies**:
   Install all the required dependencies for both backend and frontend:
   
   - For the frontend (React):
     ```bash
     cd client
     npm install
     ```

   - For the backend (Node.js/Express):
     ```bash
     cd server
     npm install
     ```

4. **Setup Environment**:
   - Create a `.env` file in the `server` directory and add the necessary configurations for MongoDB (e.g., `MONGODB_URI`, `PORT`).

5. **Run the Application**:

   - Start the server:
     ```bash
     cd server
     npm start
     ```

   - Start the client:
     ```bash
     cd client
     npm start
     ```

   The app should now be running locally at `http://localhost:3000`.

## Usage

Once the application is running, you can interact with the Kanban board through the following actions:

- **Add a Task**: Click on the "Add Task" button to create a new task.
- **Drag and Drop**: Drag tasks between columns (e.g., from "To Do" to "In Progress").
- **Edit a Task**: Click on the task card to edit its details.
- **Delete a Task**: Click the delete icon on a task to remove it from the board.
  
The board will automatically save your changes locally. Any changes made to the tasks will persist until the page is reloaded or the session is cleared.

## Folder Structure

The project has a simple structure with separate folders for the client-side (React) and server-side (Node.js/Express).

```
Kanban-Board/
├── client/               # Frontend (React) application
│   ├── public/           # Public files (index.html)
│   ├── src/              # React source code
│   │   ├── components/   # Reusable components (Task, Column, etc.)
│   │   ├── App.js        # Main React App component
│   │   ├── index.js      # Entry point for React
│   └── package.json      # Frontend dependencies
├── server/               # Backend (Node.js/Express) application
│   ├── controllers/      # API endpoint logic
│   ├── models/           # MongoDB models for tasks
│   ├── routes/           # Express routes for handling requests
│   ├── .env             # Environment variables (MongoDB URI, etc.)
│   ├── server.js        # Entry point for backend
└── README.md            # Project documentation
```

## Contributing

We welcome contributions to the Kanban Board project! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new pull request.

Please ensure that your code adheres to the existing style and includes necessary tests (if applicable).


## Contact

For any questions or inquiries, feel free to open an issue or contact the repository owner at:

- [lakshyar24](https://github.com/lakshyar24)

---

Thank you for checking out the Kanban Board project! We hope it helps you manage tasks more effectively.
