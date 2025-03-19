def add(x, y):
  return x+y
def subtract(x, y):
  return x-y
def multiplication(x, y):
  return x*y
def division(x, y):
  return x/y
def calculator():
  print("simple calculator")
  print("choose operation")
  print("1.add")
  print("2.subtraction")
  print("3.multiplication")
  print("4.division")
  while True:
    choice = input("enter choice(1/2/3/4):")
    if choice in ('1', '2', '3', '4'):
      num1=float(input("enter first number:'"))
def add(x, y):
  return x+y
def subtract(x, y):
  return x-y
def multiplication(x, y):
  return x*y
def division(x, y):
  return x/y
def calculator():
  print("simple calculator")
  print("choose operation")
  print("1.add")
  print("2.subtraction")
  print("3.multiplication")
  print("4.division")
  while True:
    choice = input("enter choice(1/2/3/4):")
    if choice in ('1', '2', '3', '4'):
      num1=float(input("enter first number:"))
      num2=float(input("enter second number:"))
      if choice=='1':
         print(f"the result is: {add(num1, num2)}")
      elif choice=='2':
         print(f"the result is: {subtract(num1, num2)}")
      elif choice=='3':
         print(f"the result is: {multiplication(num1, num2)}")
      elif choice=='4':
         print(f"the result is: {division(num1, num2)}")
    else:
      print("invalid input")
calculator()
