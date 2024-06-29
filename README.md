# JS To-Do List App

## Overview

The **JS To-Do List App** is an educational project aimed at demonstrating the practical application of JavaScript, HTML, and CSS to create a functional and interactive web application. The app allows users to manage their daily tasks efficiently through an intuitive interface, making it a valuable tool for learning and practicing front-end development. 

[try now!: https://qyuzet.github.io/js-todo-list-app/]

![image](https://github.com/Qyuzet/js-todo-list-app/assets/93258081/b178b0ae-62c4-4767-9874-01ca8bcd2eef)

![js-todo-list-app](https://github.com/Qyuzet/js-todo-list-app/assets/93258081/d294e162-fac9-4fc1-8bec-a382e2740660)

## Features

- **Add Tasks**: Users can input new tasks into the to-do list.
- **Mark as Complete**: Tasks can be marked as complete to indicate their status.
- **Delete Tasks**: Users can remove tasks from the list.
- **Local Storage**: Tasks are saved in the browser's local storage, ensuring persistence across sessions.
- **Responsive Design**: The app is designed to work well on both desktop and mobile devices.

## Installation

To run the app locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Qyuzet/js-todo-list-app.git
    ```
2. Open `index.html` in your preferred web browser.

## File Structure

- **index.html**: The main HTML file containing the structure of the app.
- **style.css**: The CSS file providing the styling for the app.
- **script.js**: The JavaScript file containing the logic and functionality of the app.

## Usage

1. Open `index.html` in a web browser.
2. Enter a task in the input field and click the "Add" button to add it to the list.
3. Click on a task to mark it as complete.
4. Use the delete button to remove a task from the list.

## Code Explanation

### HTML (`index.html`)

The HTML file sets up the basic structure of the to-do list app. It includes an input field for adding tasks, a button for submitting tasks, and an unordered list to display the tasks. Key HTML elements include:

- `<input>`: For task input.
- `<button>`: To add tasks.
- `<ul>`: To display the list of tasks.

### CSS (`style.css`)

The CSS file ensures the app has a clean and modern look. It styles the input field, buttons, and task list items to enhance user experience. Important CSS rules include:

- **Flexbox**: Used for layout management to create a responsive design.
- **Transitions**: Smooth animations for task additions and deletions.

### JavaScript (`script.js`)

The JavaScript file implements the core functionality of the app. Key functions and features include:

- **Event Listeners**: For handling user interactions such as adding, marking, and deleting tasks.
- **Local Storage Integration**: To save and retrieve tasks, ensuring data persists across sessions.
- **Task Management**:
  - **addTask()**: Adds a new task to the list and updates local storage.
  - **toggleComplete()**: Marks a task as complete or incomplete.
  - **deleteTask()**: Removes a task from the list and updates local storage.

### Detailed Explanation

#### Adding Tasks
The `addTask()` function is triggered when the user clicks the "Add" button. It creates a new task element, appends it to the task list, and saves the updated list to local storage.

#### Marking Tasks as Complete
The `toggleComplete()` function is called when a task is clicked. It toggles the task's completion status and updates the class for styling purposes.

#### Deleting Tasks
The `deleteTask()` function is triggered by clicking the delete button next to a task. It removes the task from the list and updates local storage accordingly.

## Local Storage

The app uses the browser's local storage to save tasks, ensuring that the data is persistent. The key methods include:

- `saveTasks()`: Saves the current list of tasks to local storage.
- `loadTasks()`: Loads the tasks from local storage when the app initializes.

## Responsive Design

The app is designed to be fully responsive, ensuring it works seamlessly on various devices, including desktops, tablets, and mobile phones. The use of CSS Flexbox and media queries ensures that the layout adjusts appropriately to different screen sizes.

## Academic Insights

This project demonstrates key concepts in web development, including DOM manipulation, event handling, and local storage. It serves as a practical example for computer science students to understand how front-end technologies can be integrated to create interactive web applications. Through this project, students can learn:

- **HTML5**: Structuring web content.
- **CSS3**: Styling web pages.
- **JavaScript**: Adding interactivity and handling data.
- **Local Storage**: Implementing client-side storage solutions.
- **Responsive Design**: Ensuring usability across different devices.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Qyuzet/js-todo-list-app/blob/main/LICENSE) file for details.

## Contact

For any questions or suggestions, please contact Riki Awal Syahputra at [riqyuzet@gmail.com](mailto:riqyuzet@gmail.com).

## Live Demo

You can try the app live at [https://qyuzet.github.io/js-todo-list-app/](https://qyuzet.github.io/js-todo-list-app/).

For more details and to view the code, visit the [GitHub repository](https://github.com/Qyuzet/js-todo-list-app).
