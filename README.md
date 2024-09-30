
# Todo App NodeJS

This is a simple Todo application built using **Node.js**, **Express**, and **EJS** for templating. The app allows users to add, categorize, and manage their tasks.

## Features

- Add new tasks with descriptions, categories, and due dates.
- View tasks categorized by personal, work, school, college, office, or custom categories.
- Delete selected tasks.
- Minimalistic and clean UI with Bootstrap.

## Demo

You can run the app locally by following the steps below.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SanketKumarDev/Minimal-Todo-App.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Minimal-Todo-App

   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

   By default, the app runs on `http://localhost:8000`.

## Usage

1. Open `http://localhost:8000` in your browser.
2. Add a task by entering the task description, selecting a category, and choosing a due date.
3. You can see a list of added tasks.
4. Check the boxes and click "Delete Tasks" to remove completed tasks.

## Project Structure

```
.
├── public
│   ├── css
│   │   └── style.css      # Custom styles
├── views
│   ├── index.ejs          # Main EJS template
│   ├── layout.ejs         # Layout for reusability
├── routes
│   └── tasks.js           # Task-related routes
├── app.js                 # Main server entry point
├── package.json           # Dependencies and scripts
├── README.md              # This file
```

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web framework for Node.js.
- **EJS**: Templating engine for generating HTML.
- **Bootstrap**: CSS framework for building responsive layouts.
- **MongoDB**: NoSQL database for storing tasks (optional).

## Contributing

Feel free to fork this repository and submit pull requests. Any contributions, whether it's a bug fix or new feature, are welcome.


---

### Future Improvements

- [ ] Add task editing functionality.
- [ ] Implement user authentication for personalized task lists.
- [ ] Add due date notifications.
