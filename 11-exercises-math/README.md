# Exercises Javascript (Math)

Some exercises to practice
**Mathematics Javascript**

---

## Change Base Challenge

Write a JavaScript function to convert a number from one base to another.

    function(num, initial_base, change_base)... // Between 2 - 36 = "160544", "10"

## Binary to Decimal

Write a JavaScript function to convert a binary number to a decimal number.

Hint: You can use a *replace()* function...

## Decimal to Binary, Hexadecimal and OctaL

Write a JavaScript function to convert a decimal number and you can choose to what base convert the number.

    dec_to_binhexoct  = function(n, base) // dec_to_binhexoct(12, "BIN") = "1100"

## Random number

Write a JavaScript function for randomize a integer between two numbers

Hint: Math.random() function can be good idea

    random = function(max,min) // random(10,2) = 6

## Decimal places

Write a JavaScript function to format a number up to specified decimal places

    decimals(3.233, 9) // "3.233000000"

## Max and Min Value

Write a JavaScript function to find the highest and lowest number of an array.

    maxmin([2,60,1,23,9]); // Max. es = 60, Min. es = 1 

## GCD

Write a JavaScript function to get the greatest common divisor of two integers.

    gcd(9, 3); // 3

Hint: https://en.wikipedia.org/wiki/Greatest_common_divisor

## **!!** GCD Super

*Write a JavaScript function to get the greatest common divisor of **two or more integers**.*

## LCM

Write a JavaScript function to get the least common multiple of two numbers

    lcd(10,15) // 30

Hint: https://en.wikipedia.org/wiki/Lowest_common_denominator

## **!!** LCM Super

*Write a JavaScript function to get the lowest common divisor of **two or more integers**.*

## Natural Numbers

Write a JavaScript function to find out if a number is a natural number or not

    isNaturalNum(2,4,-4,-21.1, 3.12) //true, true, false, false, false

## Write a JavaScript function to test if a number is a power of 2.
    power_of_2(16); // true
    power_of-2(11); // false

Hint: https://en.wikipedia.org/wiki/Power_of_two

## Round a Number
Write a JavaScript function to round a number to a given decimal places.
    
Hint: Use the Math.round() function

## Check integer value
Write a JavaScript function to check whether a value is an integer or not.
    Hint : Integer - A number which is not a fraction; a whole number.

    is_Int(-23) // true

## Check numeric value
Write a JavaScript function to check whether a variable is numeric or not.

    is_Numeric('abcd') // false

## Sum of array
Write a JavaScript function to calculate the sum of values in an array.

    sumArray(3,2,1); // 6
Hint: http://www.w3schools.com/jsref/jsref_reduce.asp

## Product of array
Write a JavaScript function to calculate the product of values in an array. 

    product([2,2,'a',3]); // 12

## Pythagoras
Create a Pythagorean function in JavaScript.

Hint: http://www.w3schools.com/jsref/jsref_sqrt.asp

## Binominal Coeficients
Write a JavaScript program to evaluate binomial coefficients.

    Binomial coefficient : According to Wikipedia - In mathematics, binomial coefficients are a family of positive integers that occur as coefficients in the binomial theorem. They are indexed by two nonnegative integers; the binomial coefficient indexed by n and k. Under suitable circumstances the value of the coefficient is given by the expression : n!/k!(n-k)!
    binomial coefficients 

## Roman Numbers
Write a JavaScript function that Convert an integer into a Roman Numeral in javaScript.

## **!!** Roman Numbers to Integer

## UUID
Write a JavaScript function to create a UUID identifier.

Hint: new Date().getTime()...
Hint 2: https://en.wikipedia.org/wiki/Universally_unique_identifier

## Strip zeros 
Write a JavaScript function to round a number to a specified number of digits and strip extra zeros (if any).

    a = 5.0001000; //result = 5.0001

## Operations
Write a JavaScript function to make currency math with 2 numbers(add, subtract, multiply, division etc.)

## Nth root 
Write a JavaScript function to calculate the nth root of a number.

## Degrees
Write a JavaScript function to calculate degrees between 2 points with inverse Y axis.

Hint: https://en.wikipedia.org/wiki/Degree_(angle)

    pointDirection(1, 0, 1, 10) // 90

## Round up to 5
Write a JavaScript function to round up an integer value to the next multiple of 5.
Hint: Math.ceil(num/5)*5;...

    int_round5(137) // 140

## + to -
Write a JavaScript function to convert a positive number to negative number. 

## Square root
Write a JavaScript function to cast a square root of a number to an integer.

## Get the highest
Write a JavaScript function to get the highest number from three different numbers. 

Hint: Math.max...

## Percentages 
Write a JavaScript function to calculate the percentage (%) of a number. 

## Write a JavaScript function to convert degrees to radians. 
## **!!** Write a JavaScript function to convert radians to degrees.

##  Pythagoras II
Write a JavaScript function for the Pythagorean theorem. 
Hint: pythagorean(sidea, sideb);

## Power of two II
Write a JavaScript function which will return true if value are power of two.
  
    isPower_of_two(32); // true

## Range  
Write a JavaScript function to limit a value inside a certain range.

    console.log(value_limit(7, 1, 12)); // 7

## Has a decimal part?
Write a JavaScript function to check if a number is a whole number or has a decimal place.

    console.log(number_test(18.2)); //"Num has a decimal place."

## Adding commas
Write a JavaScript function to print an integer with commas as thousands separators.
    
    console.log(thousands_separators(10000.23)); // 10,000.23

## Create Color
Write a JavaScript function to create random background color.ç

Hint: *"rgb(" + x + "," + y + "," + z + ")"; / Math.random?...Math.floo?r*

## Counting digits
Write a JavaScript function to count the digits of an integer.

## Combinatorial
Write a JavaScript function to calculate the combination of n and r.
Hint: The formula is : n!/(r!*(n - r)!).

## Prime numbers
Write a JavaScript function to get all prime numbers from 0 to a specified number. 

## Hamming numbers
Write a JavaScript function to show the first twenty Hamming numbers.

Hint: *Hamming Numbers are numbers whose only prime factors are 2, 3 and 5.*

## Substract elements from array 
Write a JavaScript function to subtract elements from one another in an array.

## Divisor and modulus
Write a JavaScript function to calculate the divisor and modulus of two integers.

## Auclid Algorithm
Write a JavaScript function to calculate the extended Euclid Algorithm or extended GCD.

    In mathematics, the Euclidean algorithm[a], or Euclid's algorithm, is an efficient method for computing the greatest common divisor (GCD) of two numbers, the largest number that divides both of them without leaving a remainder. It is named after the ancient Greek mathematician Euclid, who first described it in Euclid's Elements. It is an example of an algorithm, a step-by-step procedure for performing a calculation according to well-defined rules, and is one of the oldest algorithms in common use. It can be used to reduce fractions to their simplest form, and is a part of many other number-theoretic and cryptographic calculations.

## Falling Factorial
Write a JavaScript function to calculate the falling factorial of a number.

## a + bi, Complex Numbers
Write a JavaScript program to add two complex numbers. 
     
    A complex number is a number that can be expressed in the form a + bi, where a and b are real numbers and i is the imaginary unit, that satisfies the equation i2 = −1. In this expression, a is the real part and b is the imaginary part of the complex number. 

## Lanczos approximation gamma
Write a JavaScript function to calculate Lanczos approximation gamma.

    In mathematics, the Lanczos approximation is a method for computing the Gamma function numerically, published by Cornelius Lanczos in 1964. It is a practical alternative to the more popular Stirling's approximation for calculating the Gamma function with fixed precision. 

## Complex Numbers
Write a JavaScript program to subtract two complex numbers. 


## Complex Numbers II
Write a JavaScript program to multiply two complex numbers. 


## Complex numbers III
Write a JavaScript program to divide two complex numbers. 