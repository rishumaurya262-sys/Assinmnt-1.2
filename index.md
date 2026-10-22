# Assignment 1.2 — Development Environment Setup

## Objective

To set up a web development environment on my computer and verify that the required tools are installed correctly.

## Requirements

* Visual Studio Code (VS Code)
* Node.js (LTS version)
* Live Server extension
* Prettier extension
* A web browser

## Procedure

### Step 1: Install Visual Studio Code

Visual Studio Code can be downloaded and installed from the official website: https://code.visualstudio.com/

### Step 2: Install Node.js

Download and install the LTS (Long-Term Support) version of Node.js from the official website: https://nodejs.org/

Node.js also includes npm (Node Package Manager).

### Step 3: Install VS Code Extensions

Open Visual Studio Code and install these extensions:

* Live Server
* Prettier - Code formatter

### Step 4: Create a Project Folder

Create a folder named `web-development-practice` to store the web development files.

### Step 5: Create the Required Files

Inside the project folder, create these three files:

* `index.html`
* `style.css`
* `script.js`

### Step 6: Write the Code

Add the following code to each file.

#### index.html

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

#### style.css

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

#### script.js

```javascript
function showMessage() {
    alert("Hello! Your web development environment is working.");
}
```

### Step 7: Run the HTML File

Open the `web-development-practice` folder in Visual Studio Code. Open `index.html`, right-click inside the editor, and select **Open with Live Server**. The web page should open in the default browser.

### Step 8: Verify Node.js and npm

Open the terminal in Visual Studio Code and run these commands:

```bash
node -v
npm -v
```

Both commands should display version numbers if Node.js and npm are installed correctly.

## Result

The web development environment is ready for practising HTML, CSS, and JavaScript after the required tools and extensions have been installed. The project files can be opened using Live Server, and the Node.js and npm installations can be checked using the terminal commands.

## Submission

Attach the following screenshots as proof of completion:

1. **VS Code Screenshot:** Showing the project folder and the three files.
2. **Node.js and npm Screenshot:** Showing the terminal output of `node -v` and `npm -v`.
3. **Browser Screenshot:** Showing the HTML page running using Live Server.
