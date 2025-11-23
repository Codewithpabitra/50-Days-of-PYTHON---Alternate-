### Here we will discuss about `how we can take input` from the user and can play with the input 

- For taking input we use `input()` function in python. for example 👇
```python
name = input() # help to take input from the console 
```

```python
print("Enter your name : ")
full_name = input()
```

- now print user's name by taking his/her name from the console -> 
```python
print("What is your name ? ")
name = input()
print(f"Your name is {name}") 
```

- *Important ✅ - the `input() function return string` i.e. from console it reads as a string . 
- so ,  if you want to manipulate with numbers you have to convert it explicitely. like this way 👇

```python
num1 = input("Enter first number : ") # 10 
num2 = input("Enter second number : ") # 2

sum = num1 + num2 # '10' + '2' = '102' (as all are the strings -> string concatenation will happen) 
print(f"The total sum = {sum}") # The total sum = 102
```

- Now, the correct way 👇
```python
num1 = input("Enter first number : ") #10 
num2 = input("Enter second number : ") #2

sum = int(num1) + int(num2) # 10 + 2 = 12 
print(f"The total sum = {sum}") # 12 
```

- another e.g. 👇
```python
number1 = int(input("Enter the number1 : "))
number2 = int(input("Enter the number2 : "))

print(f"The multiplication = {number1 * number2}")
```

- similar for the float numbers 👇
```python
banana_price = float(input("what the price of the banana ? "))

final_value = banana_price - (banana_price * (20/100)); # 20% discount on the banana price and calculate the final value have to pay to the vendor 

print(f"The total value have to pay to the vendor = {final_value}")
```

- so basically , `input()` to take the input from the console and `print()` to print the ouput on the console 

