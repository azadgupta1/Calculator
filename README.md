// Calculator

const a = 4;
const b = 5;
const c = 3;
const d = 1;


// Added function definition.  The function name was improved for clarity.
function calculateSum(x, y) {
    if (typeof x !== 'number' || typeof y !== 'number') {
        return "Error: Inputs must be numbers."; //Handle non-number inputs
    }
    return x + y;
}

//Using the function for better code structure and reusability.
console.log(calculateSum(a, b)); 

//Improved function name and added a more descriptive log message.
function greet() {
    console.log("Greeting from the calculator function!");
}

greet();

// Demonstrating use of other variables.  Consider a more robust calculation function if needed.
console.log("c + d =", calculateSum(c,d));

//Example of error handling:
console.log("a + 'hello' =", calculateSum(a, 'hello'));