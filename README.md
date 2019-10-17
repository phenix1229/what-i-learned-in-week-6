# what-i-learned-in-week-6
## Loops

3 parts to a loop:
1. Setup
2. Continuation check
3. Change

*Example:*
```
let num = 1;

while(num < 10){
    console.log('hello');
    num = num + 1;
}
```
`i` - common shorthand for integer

---

## Array basics

`arrayName = ['x', 'y', 'z']` - create an array

### Array methods

* `.push` - adds an item to the end of an array
* `.pop` - removes the last item from the array (no arguments needed)
* `.shift` - removes the first item in an array
* `.unshift` - inserts an item in the first index (0) of an array
  
---

## Miscellaneous

### Dot chaining
A quicker way to accomplish a task rather than assigning multiple variables.

*Example:*
```
document.querySelector('#randomId').style. color ='red'

As opposed to:

const desiredElement = document.querySelector('#randomId');
desiredElement.style.color = 'red';
```
### String interpolation

Used to insert javascript (variables, functions, booleans, return values, etc.) into a string. Place entire string (including javascript) in back ticks "`" and place javascript in curly braces "{}" preceded by "$".

*Example:*
```
console.log(`string ${javascript} string string`);
```
### String methods

* `.repeat(num)` - repeats a string the desired number of times
* `.replace('old', 'new')` - replace first instance of the desired string
* `.includes('thingToCheckFor')` - search a string to check if it contains an item 

### Converting a number to a string

`toString`

`5 + '' = '5'`

---