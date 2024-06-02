# conditional.js
its a simple task form my mentor
//Home Work Question for class 05 conditional statement

/*1.  **Basic Loops**:

- **Question**: Write a `for` loop that prints the numbers from 10 to 1 in descending order.
   - **Hint**: Use a loop counter that starts at 10 and decrements by 1 until it reaches 1.
*/

// Ans

// for (let i = 10; i >= 1; i--) {
    console.log(i);
// }



/*
2. **While Loop**:

   - **Question**: Write a `while` loop that prints the first 5 even numbers starting from 0.
   - **Hint**: Use a loop counter initialized to 0 and increment it by 2 in each iteration.
*/

// Ans

// let counter = 0;

// while (counter < 10) 
//
//{  if (counter % 2 === 0) {
//    console.log(counter);
//  }
    counter += 2;
// }


// without extra variables

// var ev = 0;
// while(ev <= 2*5-1){
//     console.log(ev);
//     ev += 2;
// }

/*
3. **Do-While Loop**:

   - **Question**: Write a `do-while` loop that prints the numbers from 1 to 5.
   - **Hint**: Ensure the condition is checked after the loop body has executed.
*/

// Ans

// let number = 1;

// do 
// {  console.log(number);
//    number++;
 // while (number <= 5);



/*
4. **Break Statement**:

   - **Question**: Write a `for` loop that prints numbers from 0 to 10, but stops the loop when the number 7 is reached.
   - **Hint**: Use an `if` statement to check if the loop counter equals 7 and then use `break`.
*/


//Ans

// for (let i = 0; i <= 10; i++) {
//    if (i === 7) {
//        break;
//    }
//    console.log(i);
// }


/*
5. **Continue Statement**:

   - **Question**: Write a `for` loop that prints numbers from 0 to 10, but skips the number 5.
   - **Hint**: Use an `if` statement to check if the loop counter equals 5 and then use `continue`.
*/


//Ans

//for (let i = 0; i <= 10; i++) {
//    if (i === 5) {
//        continue;
//    }
//    console.log(i);
// }


/*
6. **If-Else Statement**:

   - **Question**: Write an `if-else` statement that checks if a given number `x` is positive, negative, or zero, and prints an appropriate message.
   - **Hint**: Use nested `if` statements to handle all three conditions.
*/


//Ans

// let x = /* your number here */;

// if (x > 0) {
//    console.log(`${x} is positive.`);
// }
// else if (x < 0) {
//    console.log(`${x} is negative.`);
// } 
//  else {
//    console.log(`${x} is zero.`);
// }

/*
7. **Switch Statement**:

   - **Question**: Write a `switch` statement that takes a variable `day` (with values from 0 to 6) and prints the corresponding day of the week (e.g., 0 for Sunday, 1 for Monday, etc.).
   - **Hint**: Each `case` should correspond to a day of the week.
*/


//Ans

// let day = /* your day here */;

// switch(day) {
//    case 0:
//        console.log("Sunday");
//        break;
//    case 1:
//        console.log("Monday");
//        break;
//    case 2:
//        console.log("Tuesday");
//        break;
//    case 3:
//        console.log("Wednesday");
//        break;
//    case 4:
//        console.log("Thursday");
//        break;
//    case 5:
//        console.log("Friday");
//        break;
//    case 6:
//        console.log("Saturday");
//        break;
//    default:
//        console.log("Invalid day");
// }


/*
8. **Ternary Operator**:

   - **Question**: Use the ternary operator to check if a given number `y` is even or odd and print "Even" or "Odd" accordingly.
   - **Hint**: Use the modulus operator `%` to determine if the number is even or odd.
*/


//Ans

//let y = 4;
// let result = (y % 2 === 0) ? "Even" : "Odd";
// console.log(result);


/*
9. **Combining Loops and Conditions**:

 //   Question: Write a for loop that prints numbers from 1 to 20. For multiples of 3, print "Fizz" instead of the number, for multiples of 5, print "Buzz", and for multiples of both 3 and 5, print "FizzBuzz".
//  Hint: Use if, else if, and else statements to check the conditions inside the loop.

*/


//Ans

// for (let i = 1; i <= 20; i++)
// {
//    if (i % 3 === 0 && i % 5 === 0)
// {
//        console.log("FizzBuzz");
//    }
//  else if (i % 3 === 0)
// {
//        console.log("Fizz");
//    }
//  else if (i % 5 === 0)
//  {
//        console.log("Buzz");
//    }
//  else {
//        console.log(i);
//    }



/*
10. **Complex Condition**:
    - **Question**: Write an `if-else` statement that takes a variable `temperature` and prints "Cold" if the temperature is below 15, "Warm" if it’s between 15 and 25, and "Hot" if it’s above 25.
    - **Hint**: Use compound conditions with logical operators `&&` to check for the range between 15 and 25.
*/


//Ans

// let temperature = 20; 

// if (temperature < 15) 
// {
//    console.log("Cold");
// } 
// else if (temperature >= 15 && temperature <= 25)
// {
//    console.log("Warm");
// } 
//  else
// {
    console.log("Hot");
}

