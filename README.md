// Calculator

const a = 4;
const b = 5;
const c = 3;
const d = 1;

//Improved logging for better readability and debugging
console.log("Sum of a and b:", a + b);
console.log("Sum of a, b, and c:", a + b + c);
console.log("Sum of all variables:", a + b + c + d);
console.log("Difference between b and a:", b - a);
console.log("Product of a and b:", a * b);

//Added a function to perform a calculation, demonstrating a more structured approach.

function calculateSum(x,y){
  if(typeof x !== 'number' || typeof y !== 'number'){
    return "Error: Inputs must be numbers";
  }
  return x + y;
}

console.log("Sum of a and c using function:", calculateSum(a,c));

//Removed the offensive comment.


//The undefined function call 'hey()' is removed.  If this was intended to be a function it should be defined.