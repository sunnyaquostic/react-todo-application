React Todo App

A simple yet powerful Todo application built with React.js and Context API to manage state globally.

Features

Add, update, delete, and mark todos as complete.

Uses Context API for state management.

Stores todos in localStorage for persistence.

Responsive UI with Tailwind CSS.

Project Structure

src/
│-- components/
│   │-- index.js        # Exports all components
│   │-- TodoForm.jsx    # Form to add new todos
│   │-- TodoItem.jsx    # Individual todo item component
│-- contexts/
│   │-- index.js        # Exports context utilities
│   │-- TodoContext.js  # Context provider and hooks
│-- App.jsx             # Main app component
│-- App.css             # Styling
│-- main.jsx            # Entry point
│-- index.html          # HTML template

Installation

Clone the repository:

git clone https://github.com/your-username/react-todo-app.git

Navigate to the project directory:

cd react-todo-app

Install dependencies:

npm install

Usage

To start the development server, run:

npm run dev

Then, open http://localhost:5173 in your browser.

Functionality

Add Todo: Enter a task and click "Add" to add it to the list.

Edit Todo: Click the ✏️ icon, modify the text, and save.

Delete Todo: Click ❌ to remove a todo.

Mark as Complete: Check the checkbox to mark a todo as completed.

Technologies Used

React.js

Context API

Tailwind CSS

LocalStorage

Contribution

Feel free to fork this repository and submit a pull request with improvements!
