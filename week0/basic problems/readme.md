# Hello World (Python)

A simple Python program that prints "Hello, World!" to the console.

## Requirements

- Python 3.x

Check your version:

```
python --version
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```
python hello.py
```

## Output

```
Hello, World!
```

## Code

```python
print("Hello, World!")
```

## Author

Muhammad Danish Khan  
GitHub: [danishkhan1432007](https://github.com/danishkhan1432007)

#####

# Greeting Program (Python)

A simple Python program that asks for your name and greets you.

## Requirements

- Python 3.x

Check your version:

```
python --version
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```
python hello.py
```

## Example

```
What is your name? Danish
hello, Danish
```

## Code

```python
name = input("What is your name? ")

print("hello,", name)
```

## Author

Muhammad Danish Khan  
GitHub: [danishkhan1432007](https://github.com/danishkhan1432007)

#####

# Greeting Program (Python)

A simple Python program that asks for your name, cleans it up, and greets you.

## Features

- Removes extra spaces from the start and end of the name (`strip()`)
- Capitalizes the first letter of each word (`title()`)

## Requirements

- Python 3.x

Check your version:

```
python --version
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```
python hello.py
```

## Example

```
What's your name?    muhammad danish khan  
hello, Muhammad Danish Khan
```

## Code

```python
name = input("What's your name? ")

name = name.strip()
name = name.title()

print("hello,", name)
```

## Author

Muhammad Danish Khan  
GitHub: [danishkhan1432007](https://github.com/danishkhan1432007)

#####


# Greeting Program (Python)

A simple Python program that asks for your full name and greets you by your first name.

## Features

- Splits the full name into first and last name (`split(" ")`)
- Greets the user with the first name using an f-string

## Requirements

- Python 3.x

Check your version:

```
python --version
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```
python hello.py
```

## Example

```
What's your name? Danish Khan
hello, Danish
```

## Note

Enter exactly two words (first and last name). Any other input, such as one name or three names, raises a `ValueError`.

## Code

```python
name = input("What's your name? ")
first, last = name.split(" ")
print(f"hello, {first}")
```

## Author

Muhammad Danish Khan  
GitHub: [danishkhan1432007](https://github.com/danishkhan1432007)

####

# Basic Calculator (Python)

A simple Python program that takes two integers and performs addition, subtraction, multiplication, and division on them.

## Features

- Reads two integers from the user (`int(input())`)
- Prints the sum, difference, product, and quotient

## Requirements

- Python 3.x

Check your version:

```
python --version
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```
python calculator.py
```

## Example

```
Enter the value of x? 10
Enter the value of y? 5
The Addition of two integers is: 15
The Subtraction of two integers is: 5
The Product of two integers is: 50
The Division of two integers is: 2.0
```

## Note

- Only whole numbers are accepted. Entering text or a decimal (like `2.5`) raises a `ValueError`.
- Entering `0` for `y` raises a `ZeroDivisionError`.
- Division always returns a float (for example, `10 / 5` gives `2.0`).

## Code

```python
x = int(input("Enter the value of x? "))
y = int(input("Enter the value of y? "))

print("The Addition of two integers is:", x + y)
print("The Subtraction of two integers is:", x - y)
print("The Product of two integers is:", x * y)
print("The Division of two integers is:", x / y)
```

## Author

Muhammad Danish Khan  
GitHub: [danishkhan1432007](https://github.com/danishkhan1432007)

#####

# Division Program (Python)

A simple Python program that divides one integer by another and prints the result rounded to 2 decimal places.

## Features

- Reads two integers from the user (`int(input())`)
- Divides x by y
- Formats the result to 2 decimal places using an f-string (`:.2f`)

## Requirements

- Python 3.x

Check your version:

```
python --version
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```
python division.py
```

## Example

```
What's the value of x? 10
What's the value of y? 3
3.33
```

## Note

- Only whole numbers are accepted. Entering text or a decimal (like `2.5`) raises a `ValueError`.
- Entering `0` for `y` raises a `ZeroDivisionError`.

## Code

```python
x = int(input("What's the value of x? "))
y = int(input("What's the value of y? "))

z = x / y

print(f"{z:.2f}")
```

## Author

Muhammad Danish Khan  
GitHub: [danishkhan1432007](https://github.com/danishkhan1432007)

#####

# Addition Program (Python)

A simple Python program that adds two integers and prints the result with comma separators.

## Features

- Reads two integers from the user (`int(input())`)
- Adds x and y
- Formats the result with thousands separators using an f-string (`:,`)

## Requirements

- Python 3.x

Check your version:

```
python --version
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```
python addition.py
```

## Example

```
What's the value of x? 1000
What's the value of y? 2500
3,500
```

## Note

Only whole numbers are accepted. Entering text or a decimal (like `2.5`) raises a `ValueError`.

## Code

```python
x = int(input("What's the value of x? "))
y = int(input("What's the value of y? "))

z = x + y

print(f"{z:,}")
```

## Author

Muhammad Danish Khan  
GitHub: [danishkhan1432007](https://github.com/danishkhan1432007)

#####
