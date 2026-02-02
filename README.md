# program-73
def fact(n):
if n==1:
f=1
else:
f = n * fact(n-1)
return f
num = int(input("Enter an integer:"))
result = fact(num)
print("The factorial of", num, "is:", result)
output
Enter an integer:7
The factorial of 7 is: 5040
