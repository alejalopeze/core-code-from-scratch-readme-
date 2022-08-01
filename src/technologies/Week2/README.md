<h1 align="center">Javascript - Week 2</h1>
  
  
 ## Tuesday
 
 <h3>Multiply</h3>
 
```javascript
 function multiply(a, b) {
  return a * b;
}
```
 
<h3>ASCII Total</h3>

```javascript
function uniTotal(str) {
  let test = 0;
  for (let i = 0, length = str.length; i < length; i++) {
    test += str[i].charCodeAt();
  }
  return test;
}
```
## Wednesday
 
 <h3>Char From ASCII Value</h3>

```javascript
function getChar(c){
  return String.fromCharCode(c);
}
```
<h3>Binary Addition</h3>

```javascript
function addBinary(a,b) {
total= a+b;
  return total.toString(2)
}
```
<h3>Student's Final Grade</h3>

```javascript
function finalGrade (exam, projects) {
   let val=0;
  if (exam > 90 || projects > 10) {
    val = 100;
  } else if (exam > 75 && projects >= 5) {
    val = 90;
  } else if (exam > 50 && projects >= 2) {
    val = 75;
  }
  return val
  }
  ```
  
  ## Thursday
  
  <h3>Remove All Exclamation Marks From The End Of Sentence</h3>
  
  ```javascript
  function remove(string) {
  return string.replace(/!+$/, "");
}
```
 <h3>Vowel Remover</h3>
  
  ```javascript
function shortcut(string) {
  return string.replace(/[aeiou]/ig, '');
}
```
