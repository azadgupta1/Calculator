// Calculator

const a = 4;
const b = 5;
const c = 3;
const d = 1;

// Removed unused variable and extraneous text
// csn = 3;
// ok do it


// Function definition with a descriptive name
function calculateSum(x, y) {
    if (typeof x !== 'number' || typeof y !== 'number'){
        return "Error: Inputs must be numbers";
    }
    return x + y;
}

//Improved console output for clarity

console.log(`The sum of a (${a}) and b (${b}) is: ${calculateSum(a, b)}`); 

// Function call with informative output
function greet(){
    console.log("Hey there!");
}

greet();

//Example of using the function with different variables
console.log(`The sum of c (${c}) and d (${d}) is: ${calculateSum(c,d)}`);

//Example of error handling
console.log(`The sum of a and 'hello' is: ${calculateSum(a,"hello")}`);