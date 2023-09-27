# Todo-List
This is a simple Todo List application built using React. It allows users to add, edit, and delete tasks, mark tasks as completed, and filter tasks based on their completion status.

## Hoisted URL
https://main--funny-gnome-472d31.netlify.app/

## Features

- Add tasks: Users can enter new tasks in the input field and click the "Add" button to add them to the list.
- Edit tasks: Users can click the edit icon next to a task to edit its title.
- Delete tasks: Users can click the delete icon next to a task to delete it from the list.
- Mark tasks as completed: Users can check the checkbox next to a task to mark it as completed.
- Complete all tasks: Users can click the "Complete all tasks" link to mark all tasks as completed.
- Delete completed tasks: Users can click the "Delete Comp tasks" link to delete all completed tasks.
- Filter tasks: Users can use the dropdown menu to filter tasks based on their completion status.
- Task count: The total number of tasks and the number of completed tasks are displayed.

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd todo-list
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Start the application:
   ```
   npm start
   ```

5. Open your web browser and visit http://localhost:3000 to see the Todo List application.

## API

The application uses the JSONPlaceholder API to fetch and update tasks. The API endpoint used is: https://jsonplaceholder.typicode.com/todos

## Available Scripts
In the project directory, you can run:

### npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

### npm test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

### npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.

### npm run eject
Note: this is a one-way operation. Once you eject, you can't go back!

If you aren't satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
