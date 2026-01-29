# day2-python-conditional-statements
 Python Conditional Statements practice code
#Conditional Statements
# 1 if statements 
# 2 else statements
# 3 if elif else statements

#if statements perform
age=18
if(age>=18):
    print("you can vote")    # you can vote

# if else stements 
num=75
if(num%2==0):
    print(num,"is even number")    
else:
    print(num,"is odd number")    #75 is odd number

# if elif else 
num=100
if(num>=0):
    print(num,"is positive number")  #100 is positive number
elif(num<=0):
    print(num,"is negative number")
else:
    print(num,"is zero number")

#Create a User Input

#if statements perform
age=int(input("Enter a age :"))
if(age>=18):
    print("you can vote")

# if else stements 
num=int(input("Enter a Number :"))
if(num%2==0):
    print(num,"is even number")
else:
    print(num,"is odd number")

# if elif else 
num=int(input("Enter a Number :"))
if(num>=0):
    print(num,"is positive number")
elif(num<=0):
    print(num,"is negative number")
else:
    print(num,"is zero number")
