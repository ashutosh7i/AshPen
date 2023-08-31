# Ashpen: Online HTML/CSS/JS Compiler

Ashpen is an online HTML/CSS/JS compiler that allows you to write and execute HTML, CSS, and JavaScript code snippets directly in your browser. Ashpen provides a code editor, result viewer, and live rendering of your code. This README will guide you through its features, usage, and architecture.

## Features

- Three separate code editors for HTML, CSS, and JavaScript.
- Live rendering: See your code's output in real-time.
- Responsive design: Works well on various screen sizes.
- Resize functionality: Adjust the editor and result viewer sizes.
- Easy-to-use interface with a clean and intuitive layout.

## Usage

1. Open the `index.html` file in your browser.
2. In each of the three editors, write your HTML, CSS, and JavaScript code.
3. Your code will be rendered live in the result viewer.
4. Adjust the editor and viewer sizes using the resizer handle.

## Project Structure

- `index.html`: The main HTML file that displays the Ashpen interface.
- `style.css`: The CSS file responsible for styling the Ashpen interface.
- `handleResize.js`: JavaScript code for handling the resizing functionality.
- `renderEngine.js`: JavaScript code for rendering HTML, CSS, and JS in the result viewer.

## Architecture

- Ashpen uses HTML, CSS, and JavaScript to create a user-friendly interface.
- The `handleResize.js` script enables resizing of the editor and result viewer sections.
- The `renderEngine.js` script takes code from the editors, combines it, and displays it in the iframe result viewer.

## Contributing

If you have ideas for new features, Ashpen is open for contributions!
