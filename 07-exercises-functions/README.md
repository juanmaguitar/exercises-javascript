# Exercises (Functions)

## Fibonacci Challenge

The fibonacci sequence is a mathematical sequence of integers. By definition, the first two numbers in the Fibonacci sequence are 0 and 1, and each subsequent number is the sum of the previous two.

0, 1, 1, 2, 3, 5, 8, 13, ..

Define a function called `fibonacci` with a single argument `n` The function should return the nth number of the fibonacci sequence.

Hint: Use a _recursive_ function

## String Calculator

Define a function called `add` with a single argument `input`. The input to the function will be a string containing a comma-separated list of numbers. The function must return the sum of the numbers. e.g.

    add(1,2,3,4) // => 10


## Reverse Number 

Write a JavaScript function that reverse a number

    Example x = 32243;
    Expected Output : 34223 

## Is palindrome?

Write a JavaScript function that checks whether a passed string is palindrome or not
A palindrome is word, phrase, or sequence that reads the same backward as forward, e.g., madam or nurses run.

## String combinations 

Write a JavaScript function that generates all combinations of a string

    Example string : 'dog' 
    Expected Output : d,do,dog,o,og,g 

## Sort letters

Write a JavaScript function that returns a passed string with letters in alphabetical order

    Example string : 'webmaster' 
    Expected Output : 'abeemrstw'

Assume punctuation and numbers symbols are not included in the passed string.

## Uppercase First Letter

Write a JavaScript function that accepts a string as a parameter and converts the first letter of each word of the string in upper case

    Example string : 'the quick brown fox' 
    Expected Output : 'The Quick Brown Fox '

## Longest Word

Write a JavaScript function that accepts a string as a parameter and find the longest word within the string

    Example string : 'Web Development Tutorial' 
    Expected Output : 'Development'

## How many vowels

Write a JavaScript function that accepts a string as a parameter and counts the number of vowels within the string
Note : As the letter 'y' can be regarded as both a vowel and a consonant, we do not count 'y' as vowel here. 

    Example string : 'The quick brown fox' 
    Expected Output : 5

## Is prime

Write a JavaScript function that accepts a number as a parameter and check the number is prime or not
Note : A prime number (or a prime) is a natural number greater than 1 that has no positive divisors other than 1 and itself.

## What type 

Write a JavaScript function which accepts an argument and returns the type
Note : There are six possible values that typeof returns: `object`, `boolean`, `function`, `number`, `string`, and `undefined`.


## Matrix

Write a JavaScript function which returns the n rows by n columns identity matrix.

## Second lowest and second greatest

Write a JavaScript function which will take an array of numbers stored and find the second lowest and second greatest numbers, respectively.

    Sample array : [1,2,3,4,5]
    Expected Output : 2,4 

## Perfect Numbers

Write a JavaScript function which says whether a number is perfect.

> According to Wikipedia : In number theory, a perfect number is a positive integer that is equal to the sum of its proper positive divisors, that is, the sum of its positive divisors excluding the number itself (also known as its aliquot sum). Equivalently, a perfect number is a number that is half the sum of all of its positive divisors (including itself).

> Example : The first perfect number is 6, because 1, 2, and 3 are its proper positive divisors, and 1 + 2 + 3 = 6. Equivalently, the number 6 is equal to half the sum of all its positive divisors: ( 1 + 2 + 3 + 6 ) / 2 = 6. The next perfect number is 28 = 1 + 2 + 4 + 7 + 14. This is followed by the perfect numbers 496 and 8128.

## Factors

Write a JavaScript function to compute the factors of a positive integer.


## Coinify

Write a JavaScript function to convert an amount to coins.

    Sample function : amountTocoins(46, [25, 10, 5, 2, 1])
    Here 46 is the amount. and 25, 10, 5, 2, 1 are coins. 
    Output : 25, 10, 10, 1

## getExponent

Write a JavaScript function to compute the value of bn where n is the exponent and b is the bases. Accept b and n from the user and display the result.


## Unique Characters

Write a JavaScript function to extract unique characters from a string.

    Example string : "thequickbrownfoxjumpsoverthelazydog"
    Expected Output : "thequickbrownfxjmpsvlazydg"


## Occurences 

Write a JavaScript function to  get the number of occurrences of each letter in specified string.


## Binary Search

Write a function for searching JavaScript arrays with a binary search.
Note : A binary search searches by splitting an array into smaller and smaller chunks until it finds the desired value.

Hint: https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/implementing-binary-search-of-an-array
Hint: https://en.wikipedia.org/wiki/Binary_search_algorithm

## getLargerArrays

Write a JavaScript function that returns array elements larger than a number.


## getStringId

Write a JavaScript function that generates a string id (specified length) of random characters.

    Sample character list : "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789"

## Occurrencers Letter

Write a JavaScript function that accepts two arguments, a string and a letter and the function will count the number of occurrences of the specified letter within the string.

    Sample arguments : 'w3resource.com', 'o' 
    Expected output : 2 


## First not repeated

Write a JavaScript function to find the first not repeated character.

    Sample arguments : 'abacddbec' 
    Expected output : 'e' 


## Bubble Sort algorithm

Write a JavaScript function to apply Bubble Sort algorithm. 

> Note : According to wikipedia "Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that works by repeatedly stepping through the list to be sorted, comparing each pair of adjacent items and swapping them if they are in the wrong order". 

    Sample array : [12, 345, 4, 546, 122, 84, 98, 64, 9, 1, 3223, 455, 23, 234, 213]
    Expected output : [3223, 546, 455, 345, 234, 213, 122, 98, 84, 64, 23, 12, 9, 4, 1]

## Longest Country

Write a JavaScript function that accept a list of country names as input and returns the longest country name as output. 

    Sample function : Longest_Country_Name(["Australia", "Germany", "United States of America"])
    Expected output : "United States of America"

## Longest palindrome

Write a JavaScript function that returns the longest palindrome in a given string.

> Note: According to Wikipedia "In computer science, the longest palindromic substring or longest symmetric factor problem is the problem of finding a maximum-length contiguous substring of a given string that is also a palindrome. For example, the longest palindromic substring of "bananas" is "anana". The longest palindromic substring is not guaranteed to be unique; for example, in the string "abracadabra", there is no palindromic substring with length greater than three, but there are two palindromic substrings with length three, namely, "aca" and "ada".
In some applications it may be necessary to return all maximal palindromic substrings (that is, all substrings that are themselves palindromes and cannot be extended to larger palindromic substrings) rather than returning only one substring or returning the maximum length of a palindromic substring.

## doOperation

Write a JavaScript program that accepts three parameters:

1. function to be applied to the operands
2. First Operand
3. Second Operand

```
    doOperation( function(a,b) {return a+b;}, 2, 3) // 5
    doOperation( function(a,b) {return a-b;}, 10, 3) // 7
    doOperation( function(a,b) {return a*b;}, 10, 3) // 30
```

## Function name

Write a JavaScript function to get the function name.


