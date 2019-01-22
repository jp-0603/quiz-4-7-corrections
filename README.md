# Quiz 4-7 Corrections
# Quiz 4
Question 2: The correct answer is age 976. This is correct because the "age" variable is stored as the number 16 and the second age in the parentheses will lust register as text

Question 10: The correct answers that I missed are: symbol and null. Null can

Question 11:  
```
function offToCollege() {
let userCollege = prompt(`Enter your favorite college or university.`);
let userTuition = Math.NumberIsInteger(prompt(`Enter your approximate total cost of tution for all four years`));

let yearlytuition = (userTuition/4);
let result = document.getElementbyId(`off-to-college`);
result.innerHTML = `${userCollege} is a pretty expensive school! It'll cost you $ ${yearlytuition} per year!`;
}

function carpool() {

let numberOfFriends = Number.isInteger(prompt(`How many friends are coming to the movies`));
let numberSUV = Number.isInteger(prompt(`Enter the number of your friends parents that drive SUV's`));
let seatsSUV= Math.floor(numberOfFriends/numberSUV);
let seatsSedan = 
console.log(`${seatsSUV} parents who drive suvs and ${seatsSedan} parents who drive sedans are required to transport the ${numberOfFriends} friends to the movies`);
}
```
# Quiz 5
Question 1: The correct answers are !==, <=, <, >, !=, ==, >=, ===.These are relation operators because they are used in logical statements to determine wheter or not variables or values are equal or different.

Question 2: The correct answers are !, &&, and ||. These are logical operators because they are used to determine the meaning behind variables and values.

Question 6: The correct answer is D. It has one if statement and if the input does not match the initial if statement, the if statement will go to the else statements. When the grade is found, the variable:letterGrade gets named to a letter (A, B, C, D, and F)

Question 7: The correct answers were G & H. You cannot have a semi-colon after the parameter is set. Also for an if statment there has to be a open bracket after the parameters and a closing bracket after the action wished to be completed.

Question 8: The one answer I missed was 
'''
let status = (studentGrade < 88) ? "ND" : "HR";
'''
This is correct because the first value (ND) is supposed to be assigned for the initial parameters. Then HR is supposed to be the else statement and for this statement, it is true. Both cases are true resulting the function to work.
# Quiz 6 
Question 1: The correct answer is A. This is correct because the variables are already assigned a value. Putting these values as the parameters of the function will make the function only operate when the parameters are true. Since it will be true, the function wil divide a/b and will also return the value.

Question 3: The answer that I missed is Math.random. This is not a built-in parameter because the number will always be random and will not have consistency on the fucntions to be executed.

Question 6: The answer that I added to my response was that the function will not be designed to return a value. There is no indication on what the function is supposed to be executed so I made a mistake in selecting this answer.

Question 8: The answer that I missed was D. This is the correct answer because one of the variables is not defined and when the function is executed, the value will be undefined and will display undefined as well.

Question 9: The correct answer is that the Extra arguements will be ignored. This is correct because 

Question 11: The correct answer is "This is true for variables declared using const and let" . This is correct because the const declaration will always have the same value. The same thing applies to an if statement. The let declaration usually means that the value of the variable will always be equal so the same concept will apply inside that scope.

Question 12: The correct answer will be "4 or undefined will be printed to the console."

Question 15: The correct answer is A ReferenceError will occur on line 10. This is correct because 1 cannot be equal to x. x === 1 is not true because they might have the same value but are not the same operator (variable === number). 
# Quiz 7
Question 1: The answer that I missed is
