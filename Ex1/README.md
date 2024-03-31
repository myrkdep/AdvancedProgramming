# Exercise 1: Java Syntax Exercises
### Thess exercises aim to make you comfortable with the Java language using exercises from your last term.
### For these exercises, design decisions and formatting are important.
### All exercises should have a main function to run the program.

## Ex1-1:
Write a program that has an int variable named 'n' and prints this sequence:  
1  
1 2  
1 2 3  
...  
1 2 3 ... n

## Ex1-2:
Make a Triangle class and create a method named 'typeDefine' for it. This method returns the type of triangle as a string (Equilateral, Isosceles, Right Triangle, Normal).  
If the triangle is both a Right Triangle and Isosceles, you should return 'Isosceles Right Triangle'.  
For ease of use, define your variables as public and initialize them normally.

## Ex1-3:
Write a program that prints the first 9 digit prime numbers in the Fibonacci sequence. Beware that int does not support such large numbers.

## Ex1-4:
Write a program that has an array of 10 unsorted numbers and a variable named 'n'.  
First, sort this array using bubble sort.  
Then search for 'n' inside the array. If 'n' is found, it should print its position, and if it's not found, it should print 'not found'.  
Both bubble sort and binary search should be implemented as functions.

## Ex1-5:
This exercise will be completed in the class next session.  
Make a class named Contact. This class should have a name.  
Your class should have the toString method implemented so it can be printed inside the main function using print.
Make a PhoneContact and EmailContact that inherit Contact class.
toString should be implement using super.

# Grades:
### Schema
name: score1, score2, score3, score4, score5  
Description for every assignment if needed
### Note: Removed 3rd exercise due to most of the class not understanding the problem. Exercise 5 has in class grades so no points are given for it here. 

### MaralFouladi: 100 , 100 , - , 100 , - 
- Ex2 : An Equilateral Right triangle does not exist because if it's Equilateral then it means all of the sides are equal and the equation a^2 + b^2 = c^2 does not hold

### AmirHasan Shahi: 100 , 100 , - , 100 , - 		
- WELL DONE

### Alireza Sarhangi: 100 , 100 , - , 100 , - 
- Ex2 : It should check whether it's Isosceles Right Triangle or not and after that if it's not Isosceles Right Triangle , check whether it's Isosceles Triangle or right Triangle 
- Ex4 : in line 6 we can make the code more optimal if we change ( j < m - 1 ) to ( j < m - i - 1 ) , the code should print out the index of the value if the value was found , instead of printing the value itself

### Maral Gharibi: 100 , 100 , - , 100 , - 
- Ex1 : we want n rows to be printed on the terminal so it's enough for i to start from 1 instead of 0
- Ex4 : in line 43 ( mid + 1 ) should be assigned to the variable named left instead of assigning ( mid - 1 ) to it 

### AmirHossein Abdeh: 100 , 100 , - , 100 , - 
- Ex1 : it only prints ( n-1 ) lines and because of that n doesn't get printed on the last line

### Alireza Monfared: 100 , 100 , - , 100 , - 
- Ex2 : It should check whether it's Isosceles Right Triangle or not and after that if it's not Isosceles Right Triangle , check whether it's Isosceles Triangle or right Triangle
- Ex4 : its better to use variables and its functions ( like arr.size() ) instead of just typing in numbers because for example in this question your code will only work with an array that has 10 values  

### AmirHossein Siyamansoury: 100 , 100 , - , 100 , - 
- Ex1 : there is no need for s and we can print ( j+1 ) instead of s ( your code works just fine but its better to not use too much variables if we don't need to )
- Ex2 : It should check whether it's Isosceles Right Triangle or not and after that if it's not Isosceles Right Triangle , check whether it's Isosceles Triangle or right Triangle

### Mehran Deghat: 100 , 100 , - , 100 , - 
- Ex2 :  it doesn't handle the case where the sides make Isosceles Right Triangle and it's better to print the strings in english
- Ex4 : in line 32 it should print out the index that holds the value , which is ( mid ) not ( mid + 1 ) and it's better to use variables and its functions ( like arr.size() ) instead of just typing in numbers because for example in this question your code will only work with an array that has 10 values  

### Nikta Pournabi: 100 , 100 , - , 100 , -  
- WELL DONE

### Reza Raeesi: 100 , 0 , - , 100 , - 
- Ex4 : its better to use variables and its functions ( like arr.size() ) instead of just typing in numbers because for example in this question your code will only work with an array that has 10 values  

### Ali Peivaste: 100 , 100 , - , 100 , - 
- Please choose file names that are relevant to the question
- Well Done

### Ali Bakhsha: 100 , 100 , - , 100 , - 
- Ex2 : it prints "ghaem" when the triangle is Isosceles Right or when its only Right triangle therefore it needs else bracket in line 12 to handle the case where the sides make only Right Triangle and not Isosceles Right Triangle and it's better to print the strings in english
- Ex4 : at the end you should return the result variable which holds the index of the value that was found

### Sarina Ahmadi: 100 , 50 , - , 0 , - 
- Please choose file names that are relevant to the question and send the files in the order of the questions they correspond to
- Ex2 : it doesn't handle the case where the sides make Equilateral Triangle , the line 13 condition is for checking if we CAN make the triangle out of the given sides , the bracket } in line 17 makes the further codes to not be in the function therefore resulting in an error , there is no need for ( return; ) in line 16 and the elseif in line 18 should be replaced with if 
- Ex4 : i didn't find the file for this assignment 

### Shayan JafarPour: 100 , 100 , - , 100 , - 
- Ex1 : square root of x means √x and x in the power of 2 means x^2 , in java the AND symbol is && , in this example we cant just persume the values are sorted we should either sort them or handle all the cases with diffrent values that sides can get
- Ex4 : in line 7 we can make the code more optimal if we change ( j < size - 1 ) to ( j < size - i - 1 )

### Abdul Aziz Halimi: 100 , 70 , - , 100 , - 
- Ex3 : Incomplete implementation with logic errors, lacking string return for triangle type and inconsistent output messages.

### Mohhammad Fakhrai: 100, 80, -, 100, -
- Ex2 :In the 'typeDefine' method, it's defined to return the type of triangle as a string instead of directly printing it.
