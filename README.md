# Practice
print('''Twinkle, twinkle, little star,                   #Question # 01
                How I wonder what you are!
                             Up above the world so high,
                             Like a diamond in the sky.                             
Twinkle, twinkle, little star,
                How I wonder what you are!''')
               
               Twinkle, twinkle, little star,                    
                How I wonder what you are!
                             Up above the world so high,
                             Like a diamond in the sky.
 Twinkle, twinkle, little star,
                How I wonder what you are!

import sys                                               #Question # 02
print("Python version")
print (sys.version)
print("Version info.")
print (sys.version_info)

Python version
3.8.10 (default, Sep 28 2021, 16:10:42) 

Version info.
sys.version_info(major=3, minor=8, micro=10, releaselevel='final', serial=0)


import datetime                                          #Question # 03
now = datetime.datetime.now()
print ("Current date and time : ")
print (now.strftime("%Y-%m-%d %H:%M:%S"))

Current date and time : 
2021-10-24 19:51:21


from math import pi                                       #Question # 04
r = float(input ("Enter radius of circle : "))
print ("The area of the circle with radius " + str(r) + " is: " + str(pi * r**2))

Enter radius of circle : 
9
The area of the circle with radius 9.0 is: 254.46900494077323


fname = input("Input your First Name : ")               #Question # 05
lname = input("Input your Last Name : ")
print ("Hello  " + lname + " " + fname)

Input your First Name : 
Younus
Input your Last Name : 
Amber
Hello  Amber Younus


a = int(input("enter first number: "))                  #Question # 06
b = int(input("enter second number: "))
sum = a + b
print("sum:", sum)
enter first number: 
44
enter second number: 
55
sum: 99


Eng = int(input ("Enter English Marks : "))              #Question # 07
Maths = int(input ("Enter Maths Marks : "))
Isl = int(input ("Enter Islamiat Marks : "))
GK = int(input ("Enter GK Marks : "))
Urdu = int(input ("Enter Urdu Marks : "))
total_marks = 500
marks_obtained = Eng + Maths + Isl + GK + Urdu
percentage = marks_obtained / total_marks * 100
print ("Total Marks Obtained=",marks_obtained,"out of 500")
print (" Percentage=" ,percentage)
if(percentage > 80 and percentage < 100):
           print ("Grade A+")
elif( percentage >70 and percentage < 80):
           print ("Grade A")
elif( percentage > 60 and percentage < 70):
           print ("Grade B")
elif( percentage > 50 and percentage < 60):
           print ("Grade C")
elif( percentage > 40 and percentage < 50):
           print ("Grade C")
else:
           print("Failed")


Enter English Marks : 
89
Enter Maths Marks : 
78
Enter Islamiat Marks : 
98
Enter GK Marks : 
85
Enter Urdu Marks : 
79
Total Marks Obtained= 429 out of 500
 Percentage= 85.8
Grade A+


num = int(input("Enter a number: "))                  #Question # 08
if (num % 2) == 0:
   print("{0} is Even".format(num))
else:
   print("{0} is Odd".format(num))

Enter a number: 
7
7 is Odd


Car = ["Ferrari", "Lamborghini ", "Porsche", "Jensen"]  #Question # 09
print("The length of the list is:", len(Car))

The length of the list is: 4


list1 = [11, 5, 17, 18, 23]                             #Quesetion # 10
total = sum(list1)
print("The Sum of all numeric items in given list: ", total)

10
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
/tmp/ipykernel_564/2610800130.py in <module>
      1 list1 = [11, 5, 17, 18, 23]
----> 2 total = sum(list1)
      3 print("The Sum of all numeric items in given list: ", total)
TypeError: 'int' object is not callable

  
list1 = [10, 20, 40, 145, 99]                         #Question # 11
print("Largest element is:", max(list1))

Largest element is: 145



a=[1,1,2,3,5,8,13,21,34,55,89]                        #Question # 12
for i in a:
    if i < 5:
        print(i)
             
1
1
2
3
In [ ]:
​
14
