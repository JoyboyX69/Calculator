# Simple Web Application (Calculator)

 Basic Front-End (No Back-End) - The application is entirely client-side. HTML provides the structure, CSS handles the styling, and JavaScript manages the application logic. No server-side components are present.


## Features

- Basic Arithmetic Operations: Addition, subtraction, multiplication, division, percentage calculation.

- Clear/Delete Functionality: Ability to clear the input field or delete the last entered character.

- Input Handling: Accepts numerical and operator inputs.

- Display: Shows the current input and the result of calculations.

## Tech Stack

**Client:** HTML, CSS, JavaScript

## Objective 

Create a functional calculator web application with basic arithmetic operations.

## Acknowledgements

 ### HTML Structure (index.html):
   
  - Generate the HTML structure for the calculator. Include an input field (textbox) to display the numbers and results, and buttons for numbers (0-9), operators (+, -, *, /, %), clear (AC), delete (DEL), decimal point (.), and equals (=). Use semantic HTML elements where appropriate. Ensure the HTML is well-formed and accessible.
        - 
 
 
 ### CSS Styling (style.css):

- Create a visually appealing and user-friendly     layout using CSS. Style the input field and buttons for clear visibility and easy interaction. Use a responsive design approach to ensure the calculator works well on different screen sizes. Focus on a clean and intuitive design.

### JavaScript Logic (script.js):
    
   - Implement the core calculator logic using JavaScript.

- Event Listeners: Attach event listeners to each button to detect clicks.

 - Input Handling: When a number or operator button is clicked, append its value to the input field.

  - Calculation: When the equals (=) button is clicked, evaluate the expression in the input field using the `eval()` function (with appropriate error handling). Display the result in the input field.

   - Clear/Delete Functionality: Implement the clear (AC) button to reset the input field and the delete (DEL) button to remove the last character.

   - Error Handling: Implement error handling to catch invalid expressions (e.g., division by zero) and display an appropriate error message.

### Testing:

- After generating the code, test the calculator thoroughly to ensure all operations work correctly and that error handling is functioning as expected. Verify the calculator's responsiveness on different devices.

### Deployment (Optional):

- If desired, provide instructions on how to deploy the calculator to a web server or a platform like Netlify or GitHub Pages.



