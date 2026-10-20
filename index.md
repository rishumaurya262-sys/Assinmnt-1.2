# Assignment 1.2 — Development Environment Setup

## Objective

To set up a web development environment on my computer and verify that all the required tools are installed correctly.

## Requirements

1. Visual Studio Code (VS Code)
2. Node.js (LTS version)
3. Live Server extension
4. Prettier extension
5. A web browser

## Procedure

**Step 1: Install Visual Studio Code**

I downloaded and installed Visual Studio Code from the official website: https://code.visualstudio.com/

**Step 2: Install Node.js**

I downloaded and installed the LTS (Long-Term Support) version of Node.js from https://nodejs.org/. Node.js also installed npm (Node Package Manager).

**Step 3: Install VS Code Extensions**

I opened Visual Studio Code and installed the following extensions:

* Live Server
* Prettier - Code formatter

**Step 4: Create a Project Folder**

I created a folder named `web-development-practice` to store my web development files.

**Step 5: Create the Required Files**

Inside the project folder, I created the following three files:

* `index.html`
* `style.css`
* `script.js`

**Step 6: Write the Code**

I added HTML code to `index.html`, CSS code to `style.css`, and JavaScript code to `script.js`.

### index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to My Web Development Practice</h1>
    <p>This is my first web development project.</p>
    <button onclick="showMessage()">Click Me</button>

    <script src="script.js"></script>
</body>
</html>
```

### style.css

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f8ff;
    text-align: center;
    padding: 50px;
}

h1 {
    color: #1e3a8a;
}

p {
    font-size: 18px;
    color: #333333;
}

button {
    background-color: #2563eb;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
```

### script.js

```javascript
function showMessage() {
    alert("Hello! Your web development environment is working.");
}
```

**Step 7: Run the HTML File**

I opened the `web-development-practice` folder in Visual Studio Code. Then, I opened `index.html`, right-clicked inside the editor, and selected **Open with Live Server**. The web page opened in my default browser.

**Step 8: Verify Node.js and npm**

I opened the terminal in Visual Studio Code and executed the following commands:

```bash
node -v
npm -v
```

Both commands displayed their installed version numbers, confirming that Node.js and npm were installed successfully.

## Result

The web development environment was set up successfully. Visual Studio Code, Node.js, Live Server, and Prettier were installed. The required project folder and files were created, and the HTML page was tested in a browser using Live Server.

## Submission

The following screenshots will be submitted as proof of completion:

1. Screenshot of Visual Studio Code showing the project folder and the three files.
2. Screenshot of the terminal showing the output of `node -v` and `npm -v`.
3. Screenshot of the HTML page running in the web browser using Live Server.
4.