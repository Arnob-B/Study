# Jadavpur University
## Session 2024-25, Odd Semester
### Assembly and Machine Language Lab
# Assignment 1

1. Write an Assembly Language Program to add two sixteen-bit numbers. The numbers are stored in DS: 0030H and DS: 0040H. Store the result in DS: 0050H, DS: 0051H, and DS: 0052H.[soln](./assignment1/q1.asm)
2. Write an Assembly Language Program to subtract an 8-bit numbers stored in DS: 0030H from a number stored in DS: 0040H using 2’s complement method. Store the result in DS: 0050H, and DS: 0051H.[soln](./assignment1/q2.asm)
3. Write a program to transfer a block of 8 data bytes from memory location DS: 0030H to DS: 0040H.[soln](./assignment1/q3.asm)
4. Write an 8086 Assembly Language Program for the addition of 7 eight-bit numbers stored from DS: 0030H. Store the result in DS: 0050H and DS: 0051H.[soln](./assignment1/q4.asm)
5. Write an 8086 Assembly Language Program for the addition of 5 sixteen-bit numbers stored from DS: 0030H. Store the result in DS: 0050H, DS: 0051H, DS: 0052H.[soln](./assignment1/q5.asm)
6. Write an Assembly Language Program for the addition of five BCD numbers stored from DS: 0030H. Store the result in DS: 0040H and DS: 0041H.[soln](./assignment1/q6.asm)
7. Write an Assembly Language Program to subtract a BCD number stored in DS: 0040H from a BCD number stored in DS: 0050H. Store the result in DS: 0060H and DS: 0061H. [soln](./assignment1/q7.asm)
8. Write an Assembly Language Program to multiply two eight bit number stored in DS: 0040H and DS: 0050H. Store the result from DS: 0060H.[soln](./assignment1/q8.asm)
9. Write an Assembly Language Program to multiply two sixteen bit number stored in DS:0040H and DS:0050H. Store the result from DS: 0060H.[soln](./assignment1/q9.asm)
10. Write an Assembly Language Program to divide 88H by 33H. Store the quotient in DS: 0060H and remainder in DS: 0061H.[soln](./assignment1/q10.asm)
11. Write an Assembly Language Program to divide 2222H by 55H. Store the quotient from DS: 0060H and remainder in DS: 0062H.[soln](./assignment1/q11.asm)
---
# Assignment 2
1. Write an Assembly Language Program to count the number of occurrence of 55H in a string of eight data bytes. The starting address of string is DS: 0030H. Store the count value in DS:0040H.[soln using scasb](./assignment2/1_using_scasb.asm),[soln using cmp](./assignment2/1_using_cmp.asm)
2. Write an Assembly Language Program to find out the location where 55H is placed in a string of eight data bytes. The starting address of string is DS: 0030H.[soln](./assignment2/2.asm)
3. Write an Assembly Language Program to compare two strings. The first string is stored from memory location DS: 0030H and the second sting is stored from DS: 0040H. Consider that the first byte of both strings contain the number of bytes contained in that string. If both strings are found equal, then show a value FFFFH in address DS: 0050H, otherwise show 1111H. [soln](./assignment2/3.asm)
4. Write an Assembly Language Program to check if a string of five data bytes is palindrome or not. The string is stored from memory location DS: 0030H. If the string is found to be palindrome then place FFFFH in addresses DS: 0040H otherwise place 1111H.[soln](./assignment2/4.asm)
5. Write an Assembly Language Program to count the number of positive and negative numbers present in a series of eight data bytes. The starting address of the series is DS: 0040H. Store the count value of positive number in DS: 0040H and count value of negative number in DS: 0041H.[soln](./assignment2/5.asm)
6. Write an Assembly Language Program to separate the odd and even numbers from a series of 7 data bytes. The starting address of the series is DS: 0030H. Store the even numbers from DS: 0040H and the odd numbers from DS: 0050H.[soln](./assignment2/6.asm)
7. Write an Assembly Language Program to convert an 8-bit number stored in DS: 0030H into its equivalent ASCII value. Store the converted code from DS: 0050H.[soln](./assignment2/7.asm)
8. Write an Assembly Language Program to find out the square root of a number stored in DS: 0030H. Store the result in DS: 0040H.
9. Fibonacci series is defined as:[soln](./assignment2/9.asm)
> F(i) = F(i-1) + F(i-2); for all i >2 with F(1) = F(2) = 1
Write an Assembly language Program to generate the first ten elements of this sequence and store them from DS: 0030H.
---
# Assignment 3
1. Write an Assembly Language Program to find the smallest number from a series of seven data bytes stored from DS: 0030H. Store the smallest number in DS: 0040H.
2. Write an Assembly Language Program to find the largest number from a series of 7 sixteen-bit numbers stored from DS: 0030H. Store the largest number in DS: 0040H.
3. Write an Assembly Language Program to arrange a series of 7 data bytes stored from DS: 0030H in ascending order.
4. Write an Assembly Language Program to arrange a series of 7 sixteen-bits data stored from DS: 0030H in descending order.
5. Write an Assembly Language program to find the square of a number stored in DS: 0030H using LOOK-UP table. Assume that the LOOK-UP table is stored from DS: 0040H that contains the square of the numbers 0 to 9. Store the square value in DS: 0050H.[soln](./assignment3/5.asm)

|address|values|
|---|---|
|DS:0100H | 00| 
|DS:0101H | 01| 
|DS:0102H | 04| 
|DS:0103H | 09| 
|DS:0104H | 16| 
|DS:0105H | 25| 
|DS:0106H | 36| 
|DS:0107H | 49| 
|DS:0108H | 64| 
|DS:0109H | 81| 

# Assignment 4
1. Write an Assembly Language Program to add 3 X 3 matrices. Assume the matrices
are stored in the form of lists (row wise). First matrix is stored from DS:0030H and
the second matrix is stored from DS:0040.Store the result of the addition in the third
lists starting from DS:0050H.[soln](./assignment4/1.asm)
2. Write an Assembly Language Program to convert an eight bit binary number stored in
DS:0030H into its equivalent BCD number. Stored the result in DS:0040H.[soln](./assignment4/2.asm)
3. Write an Assembly program to convert a BCD number stored in DS:0030H into its
equivalent hexadecimal number. Stored the result in DS:0040H.
4. Write an Assembly program to convert a binary number stored in DS:0030H into its
equivalent gray code. Stored the result in DS:0040H.[soln](./assignment4/4.asm)
5. Write an Assembly program to find the factorial of a number stored in DS:0030H.
Stored the result in DS:0040H.[soln](./assignment4/5.asm)


