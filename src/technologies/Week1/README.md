
<h1 align="center">Introduction to programming & Javascript - Week 1</h1>
  
  
 ## Tuesday
 
 
<h3>Your date of birth in the matrix?</h3>
 
 `Year`: 1992

## Result


| 2^10 | 2^9 | 2^8 | 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1    | 1   | 1   | 1   | 1   | 0   | 0   | 1   | 0   | 0   |  0  |

`Decimal`: 1992
`Binary`: 11111001000
 
<h3>Interpreted And Compiled Programming Languages</h3>
 
 <p>In a compiled language, the target machine directly translates the program. In an interpreted language, the source code is not directly translated by the target machine. Instead, a different program, aka the interpreter, reads and executes the code.</p>

<h3>Is Java compiled or interpreted, or both?</h3>

<p>Java is both compiled and interpreted language. Java program is first compiled into bytecode which JRE can understand. ByteCode is then interpreted by the JVM making it as interpreted language.</p>

<h3>High and Low level languages</h3>

<p>High-level languages require the use of a compiler or an interpreter for their translation into the machine code. Low-level language requires an assembler for directly translating the instructions of the machine language. These languages have a very low memory efficiency.</p>

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

