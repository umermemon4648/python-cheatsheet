# Python Cheatsheet

## Data Types in Python

 **Checking Dat types in python:**
  ```py
 print(type(10))                  # Int
print(type(3.14))                # Float
print(type(1 + 3j))              # Complex
print(type('Umer'))          # String
print(type([1, 2, 3]))           # List
print(type({'name':'Umer'})) # Dictionary
print(type({9.8, 3.14, 2.7}))    # Set
print(type((9.8, 3.14, 2.7)))    # Tuple
   ```

## Built in Functions in Python

 **print() - Used to display output to the console:**
  ```py
print('Hello! Dev')
   ```
 **input() - Reads input from the user through the console:**
  ```py
name = input("Enter your name: ")
print(f"Hello! {name}")
   ```

 **len() - Returns the length of an object (such as a string, list, or tuple):**
  ```py
language = 'Python'
print(len(language))
   ```


 **int() - Converts a value to an integer:**
  ```py
my_string = "42"
my_int = int(my_string)
print(my_int)  # Output: 42
   ```

 **float() - Converts a value to a floating-point number:**
  ```py
my_string = "3.14"
my_float = float(my_string)
print(my_float)  # Output: 3.14
   ```

**str() - Converts a value to a string:**
  ```py
my_number = 42
my_string = str(my_number)
print(my_string)  # Output: "42"
   ```



**list() - Creates a list from an iterable (e.g., a string or tuple):**
  ```py
my_string = "Hello"
my_list = list(my_string)
print(my_list)  # Output: ['H', 'e', 'l', 'l', 'o']
   ```

**dict() - Creates a dictionary:**
  ```py
my_dict = dict(firstName="Muhammad", lastName="Umer")
print(my_dict)  # Output: {'firstName': 'Muhammad', 'lastName': 'Umer'}
   ```



**min() - Returns the minimum value from an iterable or multiple arguments:**
  ```py
numbers = [5, 2, 7, 1, 9]
print(min(numbers))  # Output: 1

   ```




**max() - Returns the maximum value from an iterable or multiple arguments:**
  ```py
numbers = [5, 2, 7, 1, 9]
print(max(numbers))  # Output: 9
   ```
   

**sum() - Returns the sum of all elements in an iterable:**
  ```py
numbers = [1, 2, 3, 4, 5]
print(sum(numbers))  # Output: 15

   ```


**sorted() - Returns a new sorted list from the items in an iterable:**
  ```py
numbers = [5, 2, 7, 1, 9]
sorted_numbers = sorted(numbers)
print(sorted_numbers)  # Output: [1, 2, 5, 7, 9]

   ```


**open() - Opens a file and returns a file object:**
  ```py
file = open('sample.txt','r')
content = file.read()
print(content)
file.close()
   ```

**dir() - Returns a list of valid attributes and methods of an object:**
  ```py
my_list = [1, 2, 3]
print(dir(my_list))  # Output: ['append', 'clear', 'copy', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']
   ```

## Print Format in Python

 **formatted string literals,:**
  ```py
a = 3, b= 5
print(f"{a} + {b} is {a+b}")
   ```


 **New Style String Formatting (str.format):**
  ```py
a = 3
b= 5
print("The sum of {} + {} is {}".format(a,b,a+b))
   ```