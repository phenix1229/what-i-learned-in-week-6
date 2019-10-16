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

`.repeat(num)` - repeats a string the desired number of times

`.replace('old', 'new')` - replace first instance of the desired string

### Converting a number to a string

`toString`

`5 + '' = '5'`

---