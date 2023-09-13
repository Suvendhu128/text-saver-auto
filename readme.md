# Text saver

## Html

1. Container element: This is used to group the other elements together.
2. Heading element: This is used to create a heading. The heading in this code is the text "Text Saver".
3. Text area element: This is used to create a text field where the user can enter their message. The text area element has the id attribute of "myTextarea". This id will be used to refer to the text area in the JavaScript file.
4. Social element: This is used to add social media buttons to the page. The social element has the class attribute of "social". This class will be used to style the social media buttons in the CSS file.
5. Script element: This is used to load a JavaScript file. The script element has the src attribute of "script.js". This means that the JavaScript file named "script.js" will be loaded when the page is loaded.

## Css

1. The CSS code is written in a cascading style, which means that the declarations are applied in order from top to bottom.
2. The CSS code can be used to style any HTML element.
3. The CSS code can be used to create different effects, such as shadows, borders, and gradients.

## javaScript

The JavaScript code you have given is used to save the message entered in the textarea element to the local storage. It has the following functions:

1. const textarea = document.getElementById("myTextarea"); This line of code creates a variable called textarea and assigns it the value of the element with the id of "myTextarea".

2. function saveToLocalStorage()  This line of code defines a function called saveToLocalStorage().

3. localStorage.setItem("savedText", textarea.value); This line of code saves the value of the textarea element to the local storage under the key of "savedText".

4. if (localStorage.getItem("savedText"))  This line of code checks if there is a value stored in the local storage under the key of "savedText".

5. textarSea.value = localStorage.getItem("savedText"); This line of code sets the value of the textarea element to the value stored in the local storage under the key of "savedText".

6. textarea.addEventListener("input", saveToLocalStorage); This line of code adds an event listener to the textarea element. The event listener will call the saveToLocalStorage() function whenever the value of the textarea element is changed.