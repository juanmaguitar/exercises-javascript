# Exercises (Arrays)

## is_array

Write a JavaScript function to check whether an `input` is an array or not.

    Test Data :
    console.log(is_array('w3resource')); 
    console.log(is_array([1, 2, 4, 0]));
    false
    true

## array_Clone

Write a JavaScript function to clone an array.

    Test Data :
    console.log(array_Clone([1, 2, 4, 0])); 
    console.log(array_Clone([1, 2, [4, 0]]));
    [1, 2, 4, 0] 
    [1, 2, [4, 0]]

## first


Write a JavaScript function to get the first element of an array. Passing a parameter 'n' will return the first 'n' elements of the array.

    Test Data : 
    console.log(first([7, 9, 0, -2])); 
    console.log(first([],3));
    console.log(first([7, 9, 0, -2],3));
    console.log(first([7, 9, 0, -2],6));
    console.log(first([7, 9, 0, -2],-3));
    Expected Output : 
    7
    [] 
    [7, 9, 0] 
    [7, 9, 0, -2] 
    [] 

## last

Write a JavaScript function to get the last element of an array. Passing a parameter 'n' will return the last 'n' elements of the array.

    Test Data : 
    console.log(last([7, 9, 0, -2])); 
    console.log(last([7, 9, 0, -2],3)); 
    console.log(last([7, 9, 0, -2],6));
    Expected Output : 
    -2 
    [9, 0, -2] 
    [7, 9, 0, -2]

## joinElements

Write a simple JavaScript program to join all elements of the following array into a string.

    Sample array : myColor = ["Red", "Green", "White", "Black"];
    Expected Output : 
    "Red,Green,White,Black"
    "Red,Green,White,Black"
    "Red+Green+White+Black"

## separateEven

Write a JavaScript program which accept a number as input and insert dashes (-) between each two even numbers. For example if you accept 025468 the output should be 0-254-6-8.

## sortItems

Write a JavaScript program to sort the items of an array.

    Sample array : var arr1 = [ 3, 8, 7, 6, 5, -4, 3, 2, 1 ];
    Sample Output : -4,-3,1,2,3,5,6,7,8

## mostFrequentItem

Write a JavaScript program to find the most frequent item of an array.

    Sample array : var arr1=[3, 'a', 'a', 'a', 2, 3, 'a', 3, 'a', 2, 4, 9, 3];
    Sample Output : a ( 5 times ) 


## swapCase

Write a JavaScript program which accept a string as input and swap the case of each character. For example if you input 'The Quick Brown Fox' the output should be 'tHE qUICK bROWN fOX'.

## Print elements array

Write a JavaScript program which prints the elements of the following array.
Note : Use nested for loops.

    Sample array : var a = [[1, 2, 1, 24], [8, 11, 9, 4], [7, 0, 7, 27], [7, 4, 28, 14], [3, 10, 26, 7]];
    Sample Output : 
    "row 0" 
    " 1" 
    " 2" 
    " 1"
    " 24"
    "row 1" 

## Sum squares

Write a JavaScript program to find the sum of squares of a numeric vector.

## Sum and Product

Write a JavaScript program to compute the sum and product of an array of integers.

## addItems

Write a JavaScript program to add items in an blank array and display the items.

## removeDuplicate

Write a JavaScript program to remove duplicate items from an array (ignore case sensitivity).

## showChoices

We have the following arrays :
color = ["Blue ", "Green", "Red", "Orange", "Violet", "Indigo", "Yellow "];
o = ["th","st","nd","rd"]
Write a JavaScript program to display the colors in the following way :
"1st choice is Blue ."
"2nd choice is Green."
"3rd choice is Red."

Note : Use ordinal numbers to tell their position.

## showLeapYears

Find the leap years in a given range of years.

## shuffleArray

Write a JavaScript program to shuffle an array.

## binarySearch

Write a JavaScript program to perform a binary search.

Note : A binary search or half-interval search algorithm finds the position of a specified input value within an array sorted by key value. 

    Sample array : 
    var items = [1, 2, 3, 4, 5, 7, 8, 9];
    Expected Output : 
    console.log(binary_Search(items, 1)); //0 
    console.log(binary_Search(items, 5)); //4


## sumPositions

There are two arrays with individual values, write a JavaScript program to compute the sum of each individual index value from the given arrays.

    Sample array : 
    array1 = [1,0,2,3,4];
    array2 = [3,5,6,7,8,13];
    Expected Output : 
    [4, 5, 8, 10, 12, 13] 

## findDuplicates

Write a JavaScript program to find duplicate values in a JavaScript array.

## flattenArray

Write a JavaScript program to flatten a nested (any depth) array. If you pass shallow, the array will only be flattened a single level.

    Sample Data :
    console.log(flatten([1, [2], [3, [[4]]],[5,6]])); 
    [1, 2, 3, 4, 5, 6]
    console.log(flatten([1, [2], [3, [[4]]],[5,6]], true)); 
    [1, 2, 3, [[4]], 5, 6]

## unionArray

Write a JavaScript program to compute the union of two arrays.
Sample Data :

    console.log(union([1, 2, 3], [100, 2, 1, 10]));
    [1, 2, 3, 10, 100]

## findDifferences

Write a JavaScript function to find the difference of two arrays.

    Test Data :
    console.log(difference([1, 2, 3], [100, 2, 1, 10])); 
    ["3", "10", "100"]
    console.log(difference([1, 2, 3, 4, 5], [1, [2], [3, [[4]]],[5,6]])); 
    ["6"]
    console.log(difference([1, 2, 3], [100, 2, 1, 10]));
    ["3", "10", "100"] 

## removeFalsy

Write a JavaScript function to remove. 'null', '0', '""', 'false', 'undefined' and 'NaN' values from an array.

    Sample array : [NaN, 0, 15, false, -22, '',undefined, 47, null]
    Expected result : [15, -22, 47]

## sortObjectsTitle

Write a JavaScript function to sort the following array of objects by title value.

    Sample object :

    var library = [ 
       { author: 'Bill Gates', title: 'The Road Ahead', libraryID: 1254},
       { author: 'Steve Jobs', title: 'Walter Isaacson', libraryID: 4264},
       { author: 'Suzanne Collins', title: 'Mockingjay: The Final Book of The Hunger Games', libraryID: 3245}
       ];
    Expected result :

    [[object Object] {
      author: "Suzanne Collins",
      libraryID: 3245,
      title: "Mockingjay: The Final Book of The Hunger Games"
    }, [object Object] {
      author: "Bill Gates",
      libraryID: 1254,
      title: "The Road Ahead"
    }, [object Object] {
      author: "Steve Jobs",
      libraryID: 4264,
      title: "Walter Isaacson"
    }]

## findPairSum

Write a JavaScript program to find a pair of elements (indices of the two numbers) from an given array whose sum equals a specific target number.

    Input: numbers= [10,20,10,40,50,60,70], target=50
    Output: 3, 4

## validValues

Write a JavaScript function to retrieve the value of a given property from all elements in an array.

    Sample array : [NaN, 0, 15, false, -22, '',undefined, 47, null]
    Expected result : [15, -22, 47]

## longestCommon

Write a JavaScript function to find the longest common starting substring in a set of strings.

    Sample array : console.log(longest_common_starting_substring(['go', 'google']));
    Expected result : "go"


## fillArray

Write a JavaScript function to fill an array with values (numeric, string with one character) on supplied bounds.

Test Data : 
console.log(num_string_range('a', "z", 2));
["a", "c", "e", "g", "i", "k", "m", "o", "q", "s", "u", "w", "y"]

## mergeArrays

Write a JavaScript function to merge two arrays and removes all duplicates elements.

    Test data :
    var array1 = [1, 2, 3]; 
    var array2 = [2, 30, 1]; 
    console.log(merge_array(array1, array2));
    [3, 2, 30, 1]


## removeElement

Write a JavaScript function to remove a specific element from an array.

    Test data :
    console.log(remove_array_element([2, 5, 9, 6], 5));
    [2, 9, 6]

## findArrayWithElement

Write a JavaScript function to find an array contains a specific element.

    Test data :
    console.log(remove_array_element([2, 5, 9, 6], 5));
    [2, 9, 6]

## emptyArray

Write a JavaScript script to empty an array keeping the original size.

## getNthLargest

Write a JavaScript function to get nth largest element from an unsorted array.

    Test Data :
    console.log(nthlargest([ 43, 56, 23, 89, 88, 90, 99, 652], 4));
    89


## getRandom

Write a JavaScript function to get a random item from an array.

## array_filled (numeric)

Write a JavaScript function to create a specified number of elements with pre-filled numeric value array.

    Test Data :
    console.log(array_filled(6, 0)); 
    [0, 0, 0, 0, 0, 0]
    console.log(array_filled(4, 11));
    [11, 11, 11, 11]

## array_filled (string)

Write a JavaScript function to create a specified number of elements with pre-filled string value array.

    Test Data :
    console.log(array_filled(3, 'default value')); 
    ["default value", "default value", "default value"]
    console.log(array_filled(4, 'password'));
    ["password", "password", "password", "password"]

## moveElement

Write a JavaScript function to move an array element from one position to another.

    Test Data :
    console.log(move([10, 20, 30, 40, 50], 0, 2));
    [20, 30, 10, 40, 50]
    console.log(move([10, 20, 30, 40, 50], -1, -2));
    [10, 20, 30, 50, 40]

## filterFalsy

Write a JavaScript function to filter false, null, 0 and blank values from an array.

    Test Data :
    console.log(filter_array_values([58, '', 'abcd', true, null, false, 0]));
    [58, "abcd", true]

## generateArrayLength

Write a JavaScript function to generate an array of specified length, filled with integer numbers, increase by one from starting position.

    Test Data :
    console.log(array_range(1, 4)); 
    [1, 2, 3, 4]
    console.log(array_range(-6, 4));
    [-6, -5, -4, -3]

## generateArraySteps

Write a JavaScript function to generate an array between two integers of 1 step length.

    Test Data :
    console.log(rangeBetwee(4, 7)); 
    [4, 5, 6, 7]
    console.log(rangeBetwee(-4, 7));
    [-4, -3, -2, -1, 0, 1, 2, 3, 4, 5, 6, 7]
﻿
