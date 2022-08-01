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
