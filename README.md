# Bash Command to create HTML Boilerplate

## copy and paste this bash command in your linux terminal to crea

```bash
mkdir styles scripts images && printf '<!DOCTYPE html>\n<html lang="en">\n<head>\n    <meta charset="UTF-8">\n    <meta name="viewport" content="width=device-width, nitial-scale=1.0">\n    <title>Hello World</title>\n    <link rel="stylesheet" href="styles/styles.css">\n</head>\n<body>\n     <h1 id="change" onclick="changeColor()">Hello World! Click Me</h1>\n     \n     \n     \n     \n     <script src="scripts/scripts.js"></script>\n</body>\n</html>\n' > index.html && printf '* {\n   box-sizing: border-box;\n   padding: 1em;\n}\n\nbody {\n   background-color: lightblue;\n}' > styles/styles.css && printf 'function changeColor() {\n            document.getElementById("change").style.color = "lightgreen";\n            document.body.style.backgroundColor = "black";\n            document.getElementById("change").innerHTML = "Your JavaScript works! How neat :)";\n            return false;\n        }\n' > scripts/scripts.js && code index.html
```
