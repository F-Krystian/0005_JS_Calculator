## Calculator App

This is a simple calculator application created using HTML, CSS, and JavaScript. The application provides basic arithmetic operations such as addition, subtraction, multiplication, and division.

### Features

- Addition, subtraction, multiplication, and division operations.
- Clearing the current operand.
- Deleting the last digit of the current operand.
- Resetting the calculator to its initial state.

### How to Use

1. Clone the repository or download the files to your local machine.
2. Open the `index.html` file in your web browser.

### Functionality

#### Display

- The calculator has two display areas:
  - **Previous Operand**: Displays the previously entered operand or the result of the previous operation.
  - **Current Operand**: Displays the operand currently being entered or modified.

#### Buttons

- **Number Buttons**: Click to input numbers.
- **Operator Buttons**: Click to select an arithmetic operation.
- **C Button**: Click to clear the current operand and reset the calculator.
- **CE Button**: Click to clear the current operand.
- **DEL Button**: Click to delete the last digit of the current operand.
- **= Button**: Click to perform the selected operation and display the result.

#### Arithmetic Operations

- The calculator supports basic arithmetic operations: addition, subtraction, multiplication, and division.
- The result of the operation is displayed in the "Previous Operand" area.
- After each operation, the calculator resets the "Current Operand" to start a new calculation.

### Technologies Used

- HTML
- CSS (Flexbox and Grid for layout)
- JavaScript

### Code Overview

The JavaScript code (`app.js`) contains the functionality of the calculator, including handling number inputs, operator selections, and arithmetic operations. Here's a brief overview:

- **Display Functions**: Functions to update the display areas with the current and previous operands, as well as the selected operator.
- **Input Handling Functions**: Functions to handle number inputs, clear the current operand, delete the last digit, and reset the calculator.
- **Arithmetic Functions**: Functions to perform arithmetic operations and calculate the result.
- **Event Listeners**: Event listeners to respond to user interactions with the calculator buttons.

### Layout

The calculator layout is designed using CSS (`styles.css`), leveraging both Flexbox and Grid.