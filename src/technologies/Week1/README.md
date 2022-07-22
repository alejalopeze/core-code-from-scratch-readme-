
<h1 align="center">Introduction to programming & Javascript - Week 1</h1>
  
  
 ## Tuesday

<h3>Pseudocode currency converter</h3>

```
 START
  Valor <-- GET
  BTC <-- GET FROM(https://www.coindesk.com/price/bitcoin/)
  PRINT (Valor * BTC)
 END
```
***
## Wednesday

<h3>Print special numbers</h3> 

```javascript
for (var i=0; i<101;i++){
	if (i % 2 == 0) console.log(i);
}
```
---

<h3>Bad Code</h3> 

```javascript
var cond = false;

if ((cond==true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```

<h4>Or</h4>

```javascript
var cond = false;

if ((cond)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```
<h3>Bad Code 2</h3> 

```javascript
var n = 100;

if (n == 100) {
  console.log('This is a special number!');
}else if (n < 1000 && n % 10 == 0) {
  console.log('This number is almost special');
} else {
  console.log('Just a regular number');
}
```
***
## Thursday
***
