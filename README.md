#Task 1Write a program that prints  numbers from 100 to 150 on the screen
for i in range(100,151):
   print(i)
#Task 2write a program that prints only the even numbers from 50 to 100
i=50
while i<=100:
    if i%2==0:
        print(i)
    i+=1
#Task 3 write a program that prints only the odd numbers from 100 to 150  
i=100
while i<=150:
    if i%2==1:
        print(i) 
    i+=1 
 #Task 4 write a program that prints the table of a number entered by the user using both  for loop and while loop.
num=int(input("enter a number:"))
for i in range(1,11):
     print(num,"x",i,"=",num*i)
num=int(input("enter a number:"))
i=1
while i<=10:
     print(num,"x",i,"=",num*i)
     i+=1
 #Task 5 write a program that when runs, reads input typed the user and quits only when  user types a 鈥榪uit鈥� character.
s=" "
while s!="quit":
     s=input("enter a something: ")
print("Done")
#Task 6 write a program that computes the factorial of a number entered by the user. 
fact=1
user=int(input("enter a num: "))
i=1
while i<=user:
    fact=fact*i
    i+=1
print("factorial of number",fact)
#Task 7write a program that determines whether a number (entered by the user) is prime  or not.
num =int(input("Enter a number: "))
if num<0:
     print("chk number")
else:
    i=2
    while i<num:
        if num%i==0:
             print("Not Prime")
             break
        i+=1
    else:
        print("Prime")  
 #Task 8  write a program that prints divisible numbers of a given number.     
n=int(input("enter a number:"))
for i in range(1, n + 1):
        if n % i == 0:
            print(i)
#Task 9write a program that prints Fibonacci series.
user=int(input("enter a number:"))
a=0
b=1 
count=0
while count<user:
    print(a)
    sum=a
    a=b
    b=sum+b
    count+=1
#Task 10write a program that lets user enter 10 (later any number of) numbers and then count  how many were odd and even.
def count_odd_even(numbers):
    odd_count = 0
    even_count = 0

    for number in numbers:
        if number % 2 == 0:
            even_count += 1
        else:
            odd_count += 1

    return even_count, odd_count

# Take user input for numbers
print("Enter any 10 numbers (or more):")
numbers = []
for i in range(10):
    num = int(input(f"Enter number {i+1}: "))
    numbers.append(num)

even, odd = count_odd_even(numbers)
print(f"Number of even numbers: {even}")
print(f"Number of odd numbers: {odd}")
    

              

 
      
 
