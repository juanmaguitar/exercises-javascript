# Javascript Exercises

## Calculator

Define a function called `calculator` that receives an operation and two numbers and returns the result of the operation applied to the values passed as parameters

```javascript
   calculator("suma",10,5) // 15
   calculator("resta",10,5) // 5
   calculator("multiplicacion",10,5) // 50
   calculator("division",10,5) // 2
```

## Calculator Plus

Define a function called `calculator` that receives an operation and several numbers (can be 2 or 10 or whatever) returns the result of the operation applied to the values passed as parameters

```javascript
   calculator("suma",10,5,2,3) // 20
   calculator("resta",10,5,1) // 4
   calculator("multiplicacion",10,5,2) // 100
   calculator("division",10,5) // 2
```


## getFullName

Define a function called ​`getFullName`​ that receives a `name` and a `surname` and return the string _"Your full name is "_ with the name & surname concatenated 

```javascript
   getFullName( "juanma", "garrido") // "Your full name is "juanma garrido""
```

## isNumber

Define a function called ​`isNumber`​ that receives a value and return `true` if the value received is a number

```javascript
   isNumber(3) // true
   isNumber("3") // false
   isNumber("asass") // false
```

## isString

Define a function called ​`isString`​ that receives a value and return `true` if the value received is a string

```javascript
   isString(3) // false
   isString("3") // true
   isString("asass") // true
```


## isBoolean

Define a function called ​`isBoolean`​ that receives a value and return `true` if the value received is a boolean

```javascript
   isBoolean(3) // false
   isBoolean("true") // false
   isBoolean(true) // true
```

## encodeWord

Define a function called ​`encodeWord`​ that receives a string and return the codified version of that string replacing the following characters:

- `7` instead of `T`
- `4` instead of `A`
- `5` instead of `S`
- `0` instead of `O`

## encodeWordPlus

Improve the previous function to add a random number between 0 and 1000 every 7 characters 


---