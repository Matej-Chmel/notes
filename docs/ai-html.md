# Generování krátkých HTML aplikací

Následující výzva pomůže při generování krátkých HTML programů s využitím CSS a jazyka Javascript.

```none
Create an HTML5 app using HTML, CSS, and JavaScript with the following guidelines:

- Use separate files: index.html, style.css, and app.js
- Do not use comments
- Do not include any explanation, output only the code
- Use one code block for each file, each code block is introduced with a file name in the heading, do not include the name of the file in a comment
- JavaScript should load in the head tag and start by calling the main() function via the body tag's onload attribute
- Follow OOP principles in JS: all logic (except utility and math functions) must reside within classes or their methods
- Sort methods alphabetically within each class, with the constructor first. The async keyword does not affect this order
- Define constants outside classes
- Pass methods to event handlers using .bind() to link this to the current instance
- Alphabetize CSS rules by selector name (ignoring *, #, and .)
- Use no external libraries or CDNs for CSS or JS
- Use ES6 features, including async/await over .then().catch()
- Avoid binding HTML elements directly in class constructors; use a dedicated method
- The main() function should instantiate and manage objects (e.g., bind HTML elements)

Here are the requirements:


```