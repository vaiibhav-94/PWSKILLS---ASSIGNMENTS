# PYTHON ASSIGNMENT 2  - 30 JAN 2023
# NAME : VAIBHAV CHANNE

#### 1.    Write a program to accept percentage from the user and display and the grade according to the following criteria:

           Marks             Grade
           >90                 A
           > 80 and <=90       B
           > =60 and <=80      C
           Below 60            D


#### Ans.  percentage = float(input("Enter your percentage: "))
####       if percentage > 90:
####          print("A")
####       elif percentage > 80 and percentage <= 90:
####          print("B")
####       elif percentage >= 60 and percentage <= 80:
####          print("C")
####       else:
####          print("D")


#### 2.  Write a program to accept the cost price of a bike and display the road tax to be paid according to the following criteria:

        Tax            Cost Price (in Rs.)
        15%            >10000
        10%            >5000 and <=10000
        5%             <=5000


#### Ans.   cost_price = float(input("Enter the cost price of the bike: "))
####        if cost_price > 10000:
####    	road_tax = cost_price * 0.15
####       	    print("The road tax is:", road_tax)
####        elif cost_price > 5000 and cost_price <= 10000:
####     	road_tax = cost_price * 0.10
####     	    print("The road tax is:", road_tax)
####        else:
####     	road_tax = cost_price * 0.05
####     	    print("The road tax is:", road_tax)


#### 3.  Accept any city from the user and display monuments of that city
    
          City           Monuments
           Delhi           Red Fort
           Agra            Taj Mahal
	   Jaipur           Jal Mahal


#### Ans.    city = input("Enter a city: ")
####         if city == "Delhi":
####      	print("Red Fort")
####         elif city == "Agra":
####     	print("Taj Mahal")
####         elif city == "Jaipur":
####     	print("Jal Mahal")
####         else:
####            print("Invalid Data")


#### 4. Check how many time a given number can be divided by 3 before it is less than or equal to 10.
#### Ans.   number = int(input("Enter a number: "))
####                counter = 0
####        while number > 10:
####                number = number / 3
####                counter += 1
####         print("The number can be divided by 3", counter, "times before it is less than or equal to 10.")


#### 5. Why and when to use  while loop in python give a detailed description with example
#### Ans.    The while loop in Python is used when we want to repeatedly execute a block of code  
####          as long as a given condition is true
####      Example :
####          Print i as long as i is less than 15:
####              i = 5
####          while i < 15:
####              print(i)
####          i += 1
####      The variable i is set to 0. The while loop checks the condition i < 15, and as long as it is true, the code inside the loop is executed. The value of i is             printed and then increased by 1. This process continues until the condition becomes false, which is when i becomes equal to or greater than 15. Then  the               loop ends.

#### 6. Use nested while loop to print 3 different pattern
#### Ans.   1) Diamond pattern:
####           rows = 5
####        for i in range(1, rows * 2):
####        spaces = abs(rows - i)
####        stars = rows - spaces
####     print(" " * spaces + "*" * (2 * stars - 1))

####        2) Tringle Pattern:
####     rows = 5
####     for i in range(1, rows + 1):
####     for j in range(1, i + 1):
####        print("*", end="")
####     print()

####        3) Pyramid Pattern:
####      rows = 5
####     for i in range(1, rows + 1):
####     spaces = rows - i
####      stars = 2 * i - 1
####     print(" " * spaces + "*" * stars)

#### 7.  Reverse a while loop to display numbers from 10 to 1
#### Ans.    num = 10
####            while num >= 1:
####      print(num)
###     	num = num - 1


