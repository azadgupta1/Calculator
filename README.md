// Calculator

const num1 = 4;
const num2 = 5;
const num3 = 3;
const num4 = 1;


// Function to perform addition
function add(x, y) {
    if (typeof x !== 'number' || typeof y !== 'number') {
      throw new Error('Inputs must be numbers');
    }
    return x + y;
}


console.log(add(num1, num2)); // Addition of num1 and num2

// Function to greet the user
function greet() {
    console.log("Hey there!");
}

greet(); // Call the greet function

// Function to perform subtraction
function subtract(x, y) {
    if (typeof x !== 'number' || typeof y !== 'number') {
      throw new Error('Inputs must be numbers');
    }
    return x - y;
}

console.log(subtract(num3, num4)); // Subtraction of num3 and num4