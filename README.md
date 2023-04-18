# -JAVA-SCRIPT
## 1. Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback: 'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18. 

## Enter your age: 30

## you are old enough to drive.

## Enter your age:15

## You are left with 3 years to drive
```
let age = prompt("Enter your age:");

if (age >= 18) {
  alert("You are old enough to drive.");
} else {
  let yearsLeft = 18 - age;
  alert("You are left with " + yearsLeft + " years to drive.");
}
```

## 2. Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

## Enter your age: 30

## You are 5 years older than me
```
let myAge = 40;
let yourAge = prompt("Enter your age:");

if (yourAge > myAge) {
  console.log("You are " + (yourAge - myAge) + " years older than me.");
} else if (yourAge < myAge) {
  console.log("I am " + (myAge - yourAge) + " years older than you.");
} else {
  console.log("We are the same age!");
}
```

## 3. Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

## Enter a number: 2

## 2 is an even number

## Enter a number: 9
```
let number = prompt("Enter a number:");

if (number % 2 == 0) {
  console.log(number + " is an even number");
} else {
  console.log(number + " is an odd number");
}


```