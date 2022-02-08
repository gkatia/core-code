## - Tuesday 11/01

1. Video Compilation and interpretation
2. Interpreted. The Java source code first compiled into a binary byte code using Java compiler, then this byte code runs on the JVM (Java Virtual Machine), which is a software based interpreter. So Java is considered as both interpreted and compiled.
3. 
4. X
5. It helps solving problems and it doesn´t have strict syntax and rigid coding patterns, it´s similar to the human language so we can understand it faster.
6. Declare variable year and ask user for the year he/she was born, save current year in variable currentYear, after that substract currentYear-year and print the result as the aprox. user age.
7. X
8. Flowcharts are important because they help us to study and understand difficult problems when we see them in simple diagrams.
9. X

## - Wednesday

1. X
2. Binary: 11111001110 / hexadecimal: 7ce / decimal: 1998
3. Binary: 1100101011111110 / hexadecimal: cafe
4. 
```sh
.data
	number1: .asciiz "\nEnter a number: "
	number2: .asciiz "\nEnter another number: "
	result: .asciiz "\nThe total is: "
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
		
		move $t1,$v0
		
		add $t2, $t0, $t1
		
		li $v0, 4
		la $a0, result
		syscall
		
		li $v0, 1
		move $a0, $t2
		syscall
```
5.  
```sh
.data
name_prompt:
	.asciiz	 "Enter your name "
salute:
	.asciiz	"Hello, "
name:
	.space	20	

	.text
main:
	#Print name_prompt
	li $v0, 4
	la $a0, name_prompt
	syscall

	#Read name
	li $v0, 8
	la $a0, name
	li $a1, 40
	syscall

	#Print salutation
	li $v0, 4
	la $a0, salute
	syscall

	#Print name
	li $v0, 4
	la $a0, name
	syscall

	li $v0, 10
	syscall
```

## - Thursday

Videos and github course.
