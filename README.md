# Ignite---code_Editor
This project is a Live Code Editor, developed as part of Task 1 for Ignite Company. It is designed to offer users an interactive platform to write, edit, and execute HTML, CSS, and JavaScript code in real-time.
The primary objective is to facilitate learning and experimentation with web development technologies by providing instant feedback and a seamless coding experience.

Key Features
Real-Time Code Execution: As users type their code, the output is immediately displayed within an iframe, allowing for rapid prototyping and instant feedback.
Integrated Interface: The editor is split into three distinct sections for HTML, CSS, and JavaScript, each with its own labeled textarea and icon, making it easy to identify and work with different types of code.
Responsive Design: The layout adapts to various screen sizes, ensuring a consistent and user-friendly experience on both desktop and mobile devices.
Live Output: The results of the code are rendered live in an embedded iframe, which updates dynamically as the user types.
Project Components
index.html: This file structures the layout of the editor, including the navigation bar, the code input areas, and the output display. It also includes links to external libraries such as Font Awesome for icons and Bootstrap for styling.
code-editor.js: This JavaScript file manages the real-time execution of the user's code. It captures the input from the HTML, CSS, and JavaScript textareas, combines them, and updates the content of the output iframe accordingly.
External Libraries: The project leverages external resources like jQuery, Popper.js, and Bootstrap to enhance functionality and ensure a responsive design.
How It Works
Users enter their HTML, CSS, and JavaScript code into the designated textareas. The run() function in code-editor.js retrieves this input, integrates it into the output iframe, and executes the JavaScript code using contentWindow.eval(). This immediate feedback loop helps users learn and experiment efficiently.
