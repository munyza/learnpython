# Lists 
They are a collection of items that can:
- Hold multiple values in a single variable 
- Can store different data types (numbers, strings, booleans, even other lists)
- is *ordered*
- is mutable (can change, add or remove items)

### Creating a list 
```python 
# Empty list 
my_list = []

# Lists with items 
fruits = ["apple", "banana", "cherry"]

# Mixed data types 
mixed = [10, "hello", 3.14, True]
```

### Accessing items 
- Can use index numbers (starting from 0):
```python 
fruits = ["apple","cherry","grape"]

print(fruits[0]) # apple
print(fruits[1]) # cherry 
print(fruits[2]) # grape
```

### Modifying lists 
```python 
fruits = ["apple","cherry","grape"]

fruits[1] = "mango" # change item 
print(fruits) # ['apple', 'mango', 'grape']
```

### Other useful operations 
```python
numbers = [1, 2, 3]

numbers.append(4)      # add item
numbers.insert(1, 10)  # insert at position
numbers.remove(2)      # remove item
numbers.pop()          # remove last item
print(numbers)         # [1, 10, 3]
```

### Looping through a list 
```python
fruits = ["apple","cherry","grape"]
for fruit in fruits:
    print(fruit) # will print apple, cherry, grape
```