# Calculator

const a = 4;
const b = 5;
const c = 3;
const d = 1;

//Use a function for better organization and reusability.
function calculateSum(x,y){
    if(typeof x !== 'number' || typeof y !== 'number'){
        throw new Error("Inputs must be numbers");
    }
    return x + y;
}

console.log(calculateSum(a,b)); //Use the function to calculate the sum.  Error handling included.


//Define the function before calling it.
function hey(){
    console.log("Hey there!");
}

hey();