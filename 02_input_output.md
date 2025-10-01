# Example
```python
    name = input("Enter your name")
    print("Hello", name)
    age = int(input("Enter your age: "))
    print(f"You are {age} years old.")

```
# Explanation
- The **f** is used as a formatted string, and it means to evaluate any code inside {} and put it in there. 

- The curly braces {} tell Python to replace what is inside with its value. 

- For example: if there is a variable called age = 25, then:
```python 
    age = 25
    print(f"You are {age} years old.")

```
- It is also possible to just use commas rather than using f strings for simple projects, but for large ones it is better to use strings. 

```python 
name = "Munyza"
age = 25
city = "London"

# With commas:
print("Hello", name, "you are", age, "and live in", city)

# With f-strings:
print(f"Hello {name}, you are {age}, and live in {city}")
