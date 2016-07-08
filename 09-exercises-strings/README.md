*Skylab Coders2016 - BootCamp*

---

# JavaScript String Exercises

### is_string
Write a JavaScript function to check whether an `input` is a *string or not*. Go to the editor

    console.log(is_string('w3resource')); 
    true
    console.log(is_string([1, 2, 4, 0]));
    false

### is_Blank
Write a JavaScript function to check whether a string *is blank or not*. Go to the editor

    console.log(is_Blank('')); 
    console.log(is_Blank('abc'));
    true 
    false

### string_Array
Write a JavaScript *function to split a string and convert it into an array* of words. Go to the editor

    console.log(string_to_array("Robin Singh"));
    ["Robin", "Singh"]

### truncate
Write a JavaScript function to remove specified number of characters from a string.

    console.log(truncate_string("Robin Singh",4));
    "Robi"

### abbrev_name
Write a JavaScript function *to convert* a string in *abbreviated form*.

    console.log(abbrev_name("Robin Singh"));
    "Robin S."

### protect
Write a JavaScript function to hide email addresses to protect from unauthorized user.

    console.log(protect_email("robin_singh@example.com"));
    "robin...@example.com"

### parameterize
Write a JavaScript function to *parameterize a string*.

    console.log(string_parameterize("Robin Singh from USA."));
    "robin-singh-from-usa"

### capitalize_first
Write a JavaScript function to *capitalize the first letter of a string*. 

    console.log(capitalize('js string exercises'));
    "Js string exercises"

### capitalize_words
Write a JavaScript function to *capitalize* the first letter *of each word* in a string.

    console.log(capitalize_Words('js string exercises'));
    "Js String Exercises"

### swapcase
Write a JavaScript function that takes a string which has lower and upper case letters as a parameter and *converts upper case letters to lower case*, and lower case letters to upper case.

    console.log(swapcase('AaBbc'));
    "aAbBC"

### camelize
Write a JavaScript function *to convert a string into camel case*.

    console.log(camelize("JavaScript Exercises")); 
    console.log(camelize("JavaScript exercises")); 
    console.log(camelize("JavaScriptExercises"));
    "JavaScriptExercises" 
    "JavaScriptExercises" 
    "JavaScriptExercises"

### uncamelize
Write a JavaScript function to *uncamelize* a string.

    console.log(uncamelize('helloWorld','_'));
    "hello_world"

### repeat
Write a JavaScript function to *concatenates a given string n times* (default is 1).

    console.log(repeat('Ha!',3));
    "Ha!Ha!Ha!"

### insert
Write a JavaScript function to insert a string within a string at a *particular position* (default is 1).

 
    console.log(insert('We are doing some exercises.','JavaScript ',18));
    "We are doing some exercises." 
    "JavaScript We are doing some exercises." 
    "We are doing some JavaScript exercises."

### humanized
Write a JavaScript function to humanized number (Formats a number to a human-readable string.) with the correct suffix such as 1st, 2nd, 3rd or 4th. 

    console.log(humanize_format(301)); 
    console.log(humanize_format(402)); 
    "301st" 
    "402nd"

### truncate
Write a JavaScript function to *truncates a string if it is longer than the specified number of characters*. Truncated strings will end with a translatable ellipsis sequence ("…") (by default) or specified characters. 

    console.log(text_truncate('We are doing JS string exercises.',15,'!!'))
    "We are doing !!"

### chop
Write a JavaScript function *to chop a string into chunks of a given length*.

    console.log(string_chop('w3resource',2)); 
    ["w3", "re", "so", "ur", "ce"] 

### count
Write a JavaScript function to *count the occurrence of a substring* in a string. 

    console.log(count("The quick brown fox jumps over the lazy dog", 'the'));
    Output :
    2

### HTML_scape
Write a JavaScript function to *escape a HTML* string. 

```
console.log(escape_HTML('<a href="javascript-string-exercise-17.php" target="_blank">'));
"&lt;a href=&quot;javascript-string-exercise-17.php&quot; target=&quot;_blank&quot;&gt;"
```
### formatted_string
Write a JavaScript function that can pad (left, right) *a string to get to a determined length*. 

    console.log(formatted_string('00000000',123,''));
    "12300000"

### repeat II
Write a JavaScript function to *repeat a string a specified times*. 

    console.log(repeat_string('a', 4)); 
    "aaaa" 

### special_chars
Write a JavaScript function to get a part of a string after a specified character.

    console.log(subStrAfterChars('w3resource: JavaScript Exercises', ':','a'); 
    "w3resource" 

### strip
Write a JavaScript function to *strip leading and trailing spaces* from a string.

    console.log(strip(' w3resource '));
    "w3resource"

### truncate II
Write a JavaScript function to truncate a string to a certain number of words. 

    console.log(truncate('The quick brown fox jumps over the lazy dog', 4));
    "The quick brown fox"

### alphabetize
Write a JavaScript function to alphabetize a given string. 

*Hint:Alphabetize string : An individual string can be alphabetized. This rearranges the letters so they are sorted A to Z.*

    console.log(alphabetize_string('United States'));
    "SUadeeinsttt"

### remove_first
Write a JavaScript function to r*emove the first occurrence* of a given 'search string' from a string. 

    console.log(remove_first_occurrence("The quick brown fox jumps over the lazy dog", 'the'));
    "The quick brown fox jumps over lazy dog"

### ASCIItoHEX
Write a JavaScript function to *convert ASCII to Hexadecimal* format. 

    console.log(ascii_to_hexa('12')); 
    "3132" 

### HEXtoASCII
Write a JavaScript function to *convert Hexadecimal to ASCII format*.

    console.log(hex_to_ascii('3132')); 
    console.log(hex_to_ascii('313030'));
    "12" 
    "100"

### search
Write a JavaScript function to find a word within a string. 

    console.log(search_word('The quick brown fox', 'fox')); 
    "'fox' was found 1 times." 

### check_ifEnds
Write a JavaScript function *check if a string ends with specified suffix*. 

    console.log(string_endsWith('JS PHP PYTHON','PYTHON')); 
    true

### scape_HTML II
Write a JavaScript function to *escapes special characters* **(&, <, >, ', ")** for use in HTML.

    console.log(escape_html('PHP & MySQL')); 
    "PHP &amp; MySQL"

### remove II
Write a JavaScript function to *remove non-printable ASCII* chars. 

    console.log(remove_non_ascii('äÄçÇéÉêPHP-MySQLöÖÐþúÚ'));
    "PHP-MySQL"

### remove III
Write a JavaScript function to *remove non-word characters*. 

    console.log(remove_non_word('PHP ~!@#$%^&*()+`-={}[]|\\:";\'/?><., MySQL'))
    "PHP - MySQL"

### sentence
Write a JavaScript function to *convert a string to title case*. 

    console.log(sentenceCase('PHP exercises. python exercises.')); 
    "Php Exercises. Python Exercises."

### remove_HTMLorXML
Write a JavaScript function to *remove HTML/XML tags* from string.

console.log(strip_html_tags('<p><strong><em>PHP Exercises</em></strong></p>'));
"PHP Exercises"

### zeroFill
Write a JavaScript function to create a *Zerofilled value with optional +, - sign*. 

    console.log(zeroFill(120, 5, '-')); 
    "+00120"

### compare
Write a JavaScript function to *test case insensitive* (except special Unicode characters) string comparison.

    console.log(compare_strings('abcd', 'AbcD')); 
    true

### search II
Write a JavaScript function to *create a case-insensitive search*.

    console.log(case_insensitive_search('JavaScript Exercises', 'Exercisess'))
    "Not Matched"

### uncapitalize
Write a JavaScript function to *Uncapitalize the first character of a string*. 

    console.log(Uncapitalize('Js string exercises'));
    "js string exercises"

### uncapitalize II
Write a JavaScript function to *Uncapitalize the first letter of each word* of a string.

    console.log(unCapitalize_Words('Js String Exercises'));
    "js string exercises"

### capitalize 
Write a JavaScript function to *capitalize each* word in the string. 

    console.log(capitalizeWords('js string exercises'));
    "JS STRING EXERCISES"

### capitalize II
Write a JavaScript function to *uncapitalize each word* in the string.

    console.log(unCapitalizeWords('JS STRING EXERCISES'));
    "js string exercises"

### isUpper
Write a JavaScript function to *test whether the character at the provided* (character) index is upper case. 

    console.log(isUpperCaseAt('Js STRING EXERCISES', 1));
    false

### isLower
Write a JavaScript function to *test whether the character at the provided (character) index is lower case*. 

    console.log(isLowerCaseAt ('Js STRING EXERCISES', 1));
    true

### humanize II
Write a JavaScript function to get humanized number with the correct suffix such as 1st, 2nd, 3rd or 4th. 

    console.log(humanize(1));
    console.log(humanize(20));
    "1st"
    "20th"

### startsWith
Write a JavaScript function to test whether a *string starts with a specified string*.

    console.log(startsWith('js string exercises', 'js'));
    true

### endsWith
Write a JavaScript function to *test* whether a string *ends with a specified string*.

    console.log(endsWith('JS string exercises', 'exercises'));
    true

### successor
Write a JavaScript function to get the successor of a string. Go to the editor

*Hint: The successor is calculated by incrementing characters starting from the rightmost alphanumeric (or the rightmost character if there are no alphanumerics) in the string. Incrementing a digit always results in another digit, and incrementing a letter results in another letter of the same case. If the increment generates a carry, the character to the left of it is incremented. This process repeats until there is no carry, adding an additional character if necessary.*

    string.successor("abcd") == "abce"
    string.successor("THX1138") == "THX1139"
    string.successor("< >") == "< >"
    string.successor("1999zzz") == "2000aaa"
    string.successor("ZZZ9999") == "AAAA0000"
    console.log(successor('abcd'));
    console.log(successor('3456'));
    "abce"
    "3457"
    

### guid
Write a JavaScript function to *get unique guid*(an acronym for 'Globally Unique Identifier’) of the specified length, or 32 by default.

    console.log(guid(15));
    "b7pwBqrZwqaDrex"


