# Conditions 

## Explanation 
- There are different types of conditions: if, elif and else 
- **if** is used to test the first condition 
- **elif** is used to check another condition if the previous if (or elif) was false. 
- it is possible to have multiple elif statements 
- **else** is used when none of the above conditions are true. 
- can only have one else in a chain 

```python 
age = int(input("Enter your age"))
if age >= 18:
    print("You are legally allowed to vote")
elif age < 18:
    print("You can't vote yet ")
else:
    print("Error")
```