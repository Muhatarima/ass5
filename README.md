 - 1️⃣ What is the difference between var, let, and const?
Var is the old way to declare a variable but es6 doesnot use it . instead it use let and const for variable and let is changale, can re declare but const is constant cannot re declarable .
let age=20,
const name="Medha"


    - 2️⃣ What is the spread operator (...)?
It spreads the elements or items from an array or object into indivitual parts ,meants it just unpackes all the item indivitually.
let arr1=[1,2,4];
let arr2=[...arr1,7,8] //[1,2,4,7,8]

    - 3️⃣ What is the difference between map(), filter(), and forEach()?

forEach()- a loop, does something  and returns something;
map()-loops but return a new array with changed value , does something and changes the actual value and replaces them in a new array and returns.
filter()-loops and returns the matching elements only by doing something

let numbers = [1, 2, 3, 4];
numbers.forEach(n => console.log(n)); // just prints each number
let doubled = numbers.map(n => n * 2);// [2, 4, 6, 8]
let evens = numbers.filter(n => n % 2 === 0);// [2, 4]



    - 4️⃣ What is an arrow function?
  A better and easier way to write funcion by using => , just like variable declaration 
              let add = (a, b) => a + b;

    - 5️⃣ What are template literals?
 A way to put variable inside a string using backticks (``) and (${variable}) 
  let age=21;
  const name="Medha";
  let welcome=` Hi i'm ${name} , i'm ${age} years old `;