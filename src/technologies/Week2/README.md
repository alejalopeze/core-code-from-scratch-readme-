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
 <h3>Rock Paper Scissors!</h3>
 
  ```javascript
const rps = (p1, p2) => {
  if (p1 === p2) return 'Draw!';
  if (p1 === 'rock' && p2 === 'scissors') return 'Player 1 won!';
  if (p1 === 'scissors' && p2 === 'paper') return 'Player 1 won!';
  if (p1 === 'paper' && p2 === 'rock') return 'Player 1 won!';
  return 'Player 2 won!';
};
```

<h3>Persistent Bugger</h3>

```javascript
function persistence(num) {
   let a=0;
  let ar =[];
  
  while(num > 9){
    ar = num.toString().split('');
    num=1;
     for (let i = 0; i < ar.length; i++) {
      num *= ar[i];
    }
    a++;
  }
  return a;
}
```
## Extras

<h3>Holiday VIII - Duty Free</h3>

```javascript
function dutyFree(normPrice, discount, hol){
return Math.trunc(hol/(normPrice*discount)*100);
}
```
<h3>Twice As Old </h3> 

```javascript
function twiceAsOld(dadYearsOld, sonYearsOld) {
  return Math.abs(dadYearsOld - (2 * sonYearsOld));
}
```
<h3>Valid Spacing</h3>

```javascript
function validSpacing(s) {
  if (s.length === 0) return true;
  if (s[0] === ' ' || s[s.length - 1] === ' ') return false;
  let Spaces = s.split(' ');
  for (let i = 0, length = Spaces.length; i < length; i++) {
    if (Spaces[i] === '') return false;
  }
  return true;
}
```
<h3>Fake Binary</h3>

```javascript
function fakeBin(x){
let a =[];
let result='';
a = x.toString().split('');
for(let i=0; i< a.length; i++){
  if(a[i]<5){
  result=result+0;
  }else{
  result=result+1;}
 } 
return result;
}
```
