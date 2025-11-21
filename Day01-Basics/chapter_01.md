## What is `programming` ? and `why` should you learn this ? 

- `Programming` is a way to communicate with computers to perform a particular tasks. 

- Computer a `DUMB` machine , to perform any task by it we have to give instructiions to it. `Programming is the way to give instruction to it`. 

## What is a `Program` ? 
- `Program is a set of instruction` we give to the computer or machine to perform a particular task. 

- We use different programming language to do programming , like - `python , cpp, Java, javascript` etc.  

## Why I have choosed `Python` over another programming languages ? 
- see, `Python` is a very easy and popular programming language .It feels like just english and it supports different features like `object oriented programming(OOP)` - `classes & objects` etc. also python a general purpose language i.e. it is used in diff fields like AI , machine learning , data science , web development etc. 

    So it is perfect to start with it as a newbie. 

### Now , lets write some code together - 
```python
print("hello world") # it prints on the output screen - 'hello world' 
print() # it prints on the screen with a new line '\n' 

# here '#' is used to write a single line comment - comment are not executed, it is ignored.
```    

- print() is a built in function in python . means it is already defined in python before. Our work judt to use it to print spmething on the screen. 

### Now lets talk about `Variable` and `Datatype` - pillar of any programming language . 

- `Variable` is like a `container to store data` . As everything is data and we have to play with data and after processing the data we have to come with a ouput or result , that's why we have to store data somewhere and variable is here for that. 

- And `Datatype` is something that tells about the `type of the data` we store in a variable, it can be a `integer` datatype like - `12, 0, -345` etc or `string` datatype like -` "Pabitra" or "Anything possible"` and maybe a `boolean` datatype like `true or false` etc. 

- 👇 how we define a variable in python - 
```python

# varibale_name = value 

name = "CodeWithPabitra" # String datatype - whatever in the double qoute or single quote is a string datatype 

full_name = 'Pabitra CodeWithPabitra' # String datatype

rollNo = 12 # This is a integer(int) datatype 

price_of_product = 69.80 # this is a float / real value / decimal value datatype 

isLoggedIn = True # this is a boolean datatype 
is_email_verified = False  # bollean 


print(name) # output -> CodeWithPabitra
print(full_name) # output -> Pabitra CodeWithPabitra
print(rollNo) # output -> 12
print(price_of_product) # output -> 69.80

print(isLoggedIn) #output -> True
print(is_email_verified) #output -> False 

# so the print function prints the value of the variables . 

```

- Now we are gonna use variable in the print() function itself -- 
```python 

name = 'CodeWithPabitra'
print("My name is " + name) #output -> My name is CodeWithPabitra 

```

- above `"My name is" is a string` and `name` variable is `also holds a string value` . so when we use '+' operator to add two string then they merge , also called as `string concatenation`. In this way we can use a variable dynamically in print() statement. 

- we can also use f-string to inject a variable in a string statement . like in this way 👇

```python
name = 'CodeWithPabitra'
print(f"My name is {name}") 

# output -> My name is CodeWithPabitra 

my_age = 18
print(f'I am {my_age} years old')

# Output -> I am 18 years old  
```
- we use variable name in a `{}` to inject it in a string as above.   

