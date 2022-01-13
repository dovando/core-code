# core-code-lou
Core Code bootcamp
## Introduction to programming & Javascript - Week #1
**Tuesday ANSWERS**

### 1
☑️: Compilation vs Interpretation 
Programs will depend on what do we want to develop
Compilation: Code/binary form/ ready to execute in the CPU  C. C++, Objective C, and will return an extra file (exe .ddl, etc)
Interpretation: Source Code/ .exe convert each line to a binary  PHP, JavaScript, Java, C# Python and will be read line by line each time it is called. 
### 2
Java Compiled because source code is compiled into a binary byte-code.
Java Script is software-based Interpreter
### 3
- Start
- Declare dolar = 7.60
- Declare localCurrency
- Read quetzal
- localCurrency = quetzal * dolar
- Print localCurrency
- End
------------------------------------------------------------------------------------------------
`const  dolar = 7.60;
var localCurrency;
const  monto = 70;
localCurrency = (dolar * monto);
console.log(localCurrency);`
### 4
Pseudocode: "informal code" to write programs and one benefit is that we can write it in a language that we are familiar
### 5
Great way to start learning programing and will explain what each line in the program should do
### 6
- Start
- Declare age
- Read currentYear
- Read bornYear
- age = currentYear - bornYear
- Print age
- End
---------------------------------------------------------------------------------------------------------------------
`const  currentYear = 2022;
var age;
const  bornYear = 1975;
age = (currentYear - bornYear);
console.log(age);`
### 7
Describes the process of the system or the algorithm and They are used to plan or easy understand the way the programs is built 
### 8
Communicate the ideas how the program is going to work and how other people will be involved in the process and helps to cleaning up code that is not going to work or is extra.
### 9
- High-level languages: Python, C++, Java, Visual Basic
- Low-level languages: Assembler, Machine Languaja 0-1
------------------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------------------
**Wednesday ANSWERS**
### 1
- decimal numbers: Base 10 number (0,1,2,3,4,5,6,7,8,9)
- binary numbers: Base 2 (0-1) this is use in the computer systesm (0 = off) (1 = on)
- hexadecimal numbers: Base 16 (0,1,2,3,4,5,6,7,8,9) (A= 10,B= 11,C= 12,D= 13,E= 14,F= 15)
### 2
1997
- decimal number: 1997
- binary number:  11111001101
  - 1997/2 = 998  R**1**
  - 998/2 = 499   R**0**
  - 449/2 = 249   R**1**
  - 249/2 = 124   R**1**
  - 124/2 = 62    R**0**
  - 62/2 = 31     R**0**
  - 31/2 = 15     R**1**
  - 15/2 = 7      R**1**
  - 7/2 = 3       R**1**
  - 3/2 = 1       R**1**
  - 1/2 = 0       R**1**
- hexadecimal number: 7CD
  - 1997/16 = 124.8125  124 R**13**   (0.8125*16= 13)
  - 124/16 = 7.75         7 R**12**   (0.75*16= 12)
  - 7/16 = 0.4375         0 R**7**    (0.4375*16= 7)
### 3
- decimal number: 51966
- binary numbers:  1100101011111110
  - 51966/2 = 25983  R**0**
  - 25983/2 = 12991  R**1**
  - 12991/2 = 6495   R**1**
  - 6495/2 = 3247    R**1**
  - 3247/2 = 1623    R**1**
  - 1623/2 = 811     R**1**
  - 811/2 = 405      R**1**
  - 405/2 = 202      R**1**
  - 202/2 = 101      R**0**
  - 101/2 = 50       R**1**
  - 50/2 = 25        R**0**
  - 25/2 = 12        R**1**
  - 12/2 = 6         R**0**
  - 6/2 = 3          R**0**
  - 3/2 = 1          R**1**
  - 1/2 = 0          R**1**
- hexadecimal numbers: CAFE
  - 51966/16 = 3247.875  3247 R**14**   (0.875*16= 14)
  - 3247/16 = 202.9375   202  R**15**   (0.9375*16= 15)
  - 202/16 = 12.625      12   R**10**   (0.625*16= 10)
  - 12/16 = 0.75         0    R**10**   (0.75*16= 12)
### 4
☑️
### 5
5.1 
` .data
    n1: .asciiz "Enter your first number: "
    n2: .asciiz "Enter your second number: "    
.text
    #getting first input.
    la $a0, n1
    li $v0, 4
    syscall
    li $v0, 5
    syscall
    move $t0, $v0
    #getting second input.
    la $a0, n2
    li $v0, 4
    syscall
    li $v0, 5
    syscall
    move $t1, $v0
    #end program.
    li $v0, 10
    syscall`
    
------------------------------------------------------------------------------------------------------------------------------------------------------------

5.2 
` .data
    message: .asciiz "\nDayana Ovando\n"
  .text
    main:
      li $v0, 4
      la $a0, message
      syscall`
