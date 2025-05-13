# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.


# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.

Happy Coding! 💻✨



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript DOM Manipulation</title>
    <link rel="stylesheet" href="dom-styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Interactive JavaScript DOM Manipulation</h1>
    </header>
    
    <main>
        <section id="intro">
            <h2>Welcome!</h2>
            <p id="welcome-text">This text will change when you click the button below.</p>
            <button onclick="changeText()">Change Text</button>
        </section>
        
        <section id="color-section">
            <h2>Change Background Color</h2>
            <button onclick="changeBackgroundColor()">Change Color</button>
        </section>
        
        <section id="element-section">
            <h2>Add or Remove Elements</h2>
            <button onclick="addElement()">Add Element</button>
            <button onclick="removeElement()">Remove Element</button>
            <ul id="dynamic-list"></ul>
        </section>
    </main>
    
    <footer>
        <p>Happy Coding! 💻✨</p>
    </footer>
</body>
</html>
