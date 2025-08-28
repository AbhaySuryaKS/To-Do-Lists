# To-Do List Web Application

A simple and interactive To-Do List web application where users can add, mark, delete tasks, and manage their task list efficiently. The tasks are saved in `localStorage` so they persist even after the page is reloaded.

## Features

1. **Add Tasks**: 
   - Enter a new task in the input field and click the "Add" button to add it to the list.
   - Tasks can be added with a default status of "Not Done."

2. **Mark Task as Done/Undo**:
   - Each task has a "Done" button that strikes through the task to indicate completion.
   - If a task is marked as done, the button can be clicked again to "Undo Done."

3. **Delete Individual Task**:
   - Every task has a "Delete" button to remove the task from the list.
   - A confirmation popup appears before deleting the task.

4. **Delete All Tasks**:
   - You can delete all tasks by clicking the "Delete All" button.
   - A confirmation popup appears before all tasks are deleted.

5. **Reset Input Field**:
   - Click the "Reset" button to clear the task input field.

6. **Persistent Data**:
   - All tasks are stored in `localStorage`, meaning the tasks will remain saved even if the page is reloaded or the browser is closed and reopened.

## Technologies Used

- **HTML5**: Structure and layout of the application.
- **CSS3**: Styling and user interface design.
- **JavaScript**: Core functionality, including adding tasks, marking them as done, and deleting them.

## Project Structure

- **`index.html`**: Contains the structure of the webpage including the task input field, buttons, and task list container.
- **`style.css`**: Styles the page with clean, responsive design and popup functionality.
- **`script.js`**: Handles the task management logic (adding, deleting, marking tasks as done, and storing in `localStorage`).

## How to Run

1. Download or clone the project files: `index.html`, `style.css`, and `script.js`.
2. Open `index.html` in any modern browser to view the to-do list.
3. Add tasks using the input field and manage them using the buttons provided.

## File Descriptions

### 1. `index.html`:
- The main structure of the To-Do List app with task input field, task container, and buttons for managing tasks.

### 2. `style.css`:
- Provides styling for the app, including the layout of task items, buttons, and the confirmation popup.

### 3. `script.js`:
- Contains JavaScript logic to handle all user interactions such as:
  - Adding tasks to the list.
  - Marking tasks as done.
  - Deleting individual or all tasks.
  - Showing a confirmation popup before task deletion.
  - Saving and loading tasks from `localStorage`.

## Customization

- You can change the look and feel of the app by modifying the `style.css` file.
- Adjust the task logic or add more features (e.g., priority levels or due dates) in the `script.js` file.
- Add more confirmation steps for actions like task deletion or mark all as done.

## Future Improvements

- Add task editing functionality.
- Allow users to assign priority levels to tasks (e.g., low, medium, high).
- Add categories or folders for different task lists.
- Add deadlines or reminders for tasks.
- Add an option to mark all tasks as done.

## 💡 Credits

Made by [Abhay Surya K S](https://github.com/AbhaySuryaKS/) 

## License

This project is open-source and free to use.
https://codepen.io/AbhaySuryaKS/pen/mdZRJxR
