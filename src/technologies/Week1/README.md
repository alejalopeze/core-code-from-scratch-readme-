
<h1 align="center">Introduction to programming & Javascript - Week 1</h1>
  
  
 ## Tuesday
 
<h3>Interpreted And Compiled Programming Languages</h3>
 
 <p>En un lenguaje compilado, la máquina de destino traduce directamente el programa. En un idioma interpretado, el código fuente no es traducido directamente por la máquina de destino. En cambio, un programa diferente , también conocido como el intérprete, lee y ejecuta el código.</p>

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

<h3>Your date of birth in the matrix?</h3> 

<h3>MIPS</h3> 

<h4>Create a program that adds any two given numbers provided by the user</h4>

```
  .data
	      number1: .asciiz "\nIngrese el primer numero: "
	      number2: .asciiz "\nIngrese el segundo numero: "
  .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t0, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              li $v0, 1
              move $a0, $t0
              syscall

```

<h4>Create a program that displays your name</h4>

```
 .data
        message: .asciiz "\nAlejandra, Lopez!\n"
  .text
        main:
              li $v0, 4
              la $a0, message
              syscall
```

***

## Thursday

<h3>Print special numbers</h3> 

```javascript
for (var i=0; i<101;i++){
	if (i % 2 == 0) console.log(i);
}
```


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

