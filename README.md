# calculator
Calculator design using python

a = int(input("Enter the first value- "))
b = int(input("Enter the Second value- "))
print("First value is", a, "second value is ", b)
list = ["Addition=1", "Subtraction=2", "Multiplication=3", "Division=4"]
print(list)
# a=5
# b=10
# print(a+ b)
d = int(input("choose operation- "))
if d == 1:
  print("Addition of first and second number is:", a + b)
elif d == 2:
  print("Subtraction of first and second number is:", a - b)
elif d == 3:
  print("Multiplication of first and second number is:", a * b)
elif d == 4:
  print("Dividation of first and second number is:", a / b)
else:
  print("Error 404")
  print("Choose number between 1 to 4")
