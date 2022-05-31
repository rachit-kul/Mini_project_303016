# Requirements
## Introduction
 This project is implemented using the c programming language.The main goal is to convert the given input in one of the number system to another desired number system.

## Research

For digital hardware, the natural numbering system is binary (base 2),but expressing anything in binary causes way too many bits to be used. So, it's not   practical.
Hexadecimal allows us to use 4x fewer bits, so, it is very useful.Besides no processor uses anything less than 4bits, so, hexadecimal is the most common when expressing numbers in a way that is most suitable for digital hardware.

## Defining Our System

The main aim of the program/code is to take in the input of one number system and convert it to another desired system. As we don't take inputs from any user here ,the code only tests the given functions and indicates the test cases that have passed.

## SWOT Analysis
![Image](../1_Requirements/SWOT.png)

## 4W's and 1'H
m
### Who:
 This program can be used by anyone interested for number system conversion.

### What:
 The primary use of the program is to convert from one number system to another.

### When:
 This can be used whenever one needs to encode data to enter it to the computer for any operations desired. In digital hardware, to reduce the number of bits used   this can be used to convert one system to another.

### Where:
 Can be run on any Computer with a c compiler.
 
### How:
 It uses simple logic to convert the given input in one number system to desired number system.


## Interface
The aim is to convert from the mentioned number systems to another.When the program is run the following screen is observed.
![Image](../1_Requirements/Interface.png)


## Integration
Each of the function was first written and then integrated to obtain the full functionality.The main function file main.c here automatically picks a random operation and performs the conversion.So if  a user wants to change the date he/she can update the value in the main function under the switch cases.

## Testing

Here various test cases are given to each of the following functions to make sure that it functions appropriately.It reports the number of cases failed and number of cases passed for each of the given function.

## Functional Requirements

As mentioned the code converts one number system value to another,each of the function written here needs a input data which is either binary or decimal.All the inputs are of the type long int.

## Gantt Chart
![Image](../1_Requirements/GanttChart.jpg)





