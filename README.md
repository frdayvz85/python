<h3 style="font-family: Tahoma; text-align:center;">Python Coding Exercises and Answers</h3>  

<p style="font-family: Tahoma; text-align:center;">Sharpen Your Coding Skills with Challenging Exercises and Detailed Answers</p>  

<article style="font-family: Tahoma;">
 Welcome to our coding exercises and answers repository! Whether you're preparing for technical interviews, looking to enhance your programming skills, or simply enjoy solving coding challenges, you've come to the right place. In this README file, you'll find a curated collection of coding exercises covering <b style="color: crimson;">Python </b> programming language, data structures, algorithms, and real-world scenarios. Each exercise is accompanied by a detailed answer and explanation, helping you understand the underlying concepts and improve your problem-solving abilities. Explore our collection, test your knowledge, and elevate your coding prowess!
</article>  

<h3 id="exercises" style="font-family: Georgia  ;">Exercises</h3>  

<h4 id="exercises" style="font-family: Georgia  ;">1. Please choose the correct answer(s).</h4>  

```python
print("Hello World, let's learn Python")
Print("hello world, let's learn Python")
print('hello world, let's learn Python')
print("hello world, let"s learn python")
print("hello world, let's learn Python"
print("Hello World, let's learn Python")
```

<ol style="font-family: Tahoma;">
    <li>  True, False, False, False, False, True</li>
    <li>  False, False, True, True, True, False</li>
    <li>  True, True, True, False, False, True</li>
    <li>  False, False, False, False, True, False</li>
    <li>  True, False, False, False, False, True</li>
</ol>

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

##### Answer: 1 & 5

<span style="font-family: Tahoma;">Explanation:</span>

- The first <code>print</code> statement is correct because it uses the correct capitalization and has the string properly enclosed in double quotes.

- The second <code>Print</code> statement is incorrect due to the capitalization issue. In Python, function names are case-sensitive, and the correct function name is <code>print</code> with a lowercase "p."

- The third <code>print</code> statement is incorrect due to the use of single quotes within the string without escaping them.

- The fourth <code>print</code> statement is incorrect due to a syntax error caused by mismatched quotes around the string.

- The fifth <code>print</code> statement is incorrect because it's missing the closing parenthesis.

- The sixth <code>print</code> statement is correct because it uses the correct capitalization and has the string properly enclosed in double quotes.

</p>
</details>

---

**[⬆ Back to Top](#exercises)**




<h4 id="exercises" style="font-family: Georgia  ;">2. Using a single <code>print</code> statement and a format with asterisks and spaces, how can you create following shapes in Python?</h4>  

                          *               * * *
                         * *              *   *
                        * * *             * * *

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

<h6 style="font-family: Georgia  ;">Triangle: </h6> 

```python
print('\t  *  \n\t * * \n\t* * *\n')
```

<h6 style="font-family: Georgia  ;">Square: </h6> 

```python
print('* * *\n*   *\n* * *')
```

<span style="font-family: Tahoma;">Explanation:</span>

- The shapes are created using the <code>print</code>  statement in Python. It uses the <code>\t (tab)</code> and <code>\n (newline)</code> escape sequences to control the formatting.

</p>
</details>

---

**[⬆ Back to Top](#exercises)**

<h4 id="exercises" style="font-family: Georgia  ;">3. When it comes to commenting code in Python, which of the following statements is false?</h4>  
<ol style="font-family: Tahoma;list-style-type:\1F44D;">
  <li>Python supports single-line comments using the <code>#</code> symbol.</li>
<li>Python supports multi-line comments using triple-quoted strings (e.g., <code>'''</code> or <code>"""</code>).</li>
<li>Python's docstrings are used for documenting modules, classes, and functions and are enclosed in triple-quoted strings.</li>
<li>Python supports single-line comments using the <code>//</code> symbol.</li>
<li>Python allows single-line comments using both single quotes (<code>'</code>) and double quotes (<code>"</code>).</li>
<li>Python allows multi-line comments using both single quotes (<code>'</code>) and double quotes (<code>"</code>).</li>
<li>Python encourages the use of meaningful comments to explain complex logic and improve code readability.</li>
</ol>

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

4. Python supports single-line comments using the // symbol.

<span style="font-family: Tahoma;">Explanation:</span>

- In Python, the <code>//</code> symbol is not used for single-line comments; it's used for floor division. Options a, b, c, e, f, and g are accurate regarding Python's commenting conventions, making them correct answers.
</p>
</details>

---

**[⬆ Back to Top](#exercises)**


<h4 id="exercises" style="font-family: Georgia;">4. Your task is creating a basic Canvas login simulation program in Python. The program should prompt the user to enter their username and password using two different inputs. You need to perform the following checks:</h4>  
<ol style="font-family: Tahoma;">
  <li>Check if the username is less than 5 characters. If it is, display a message indicating that the username is too short.</li>
  <li>Check if the password contains the username. If it does, display a message indicating that the password cannot contain the username.</li>
  <li>Check if the password is less than 8 characters. If it is, display a message indicating that the password is too short.</li>
  <li>If all checks pass, display a message indicating that the user has logged in successfully.</li>

</ol>

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

```python
# Prompt the user for their username and password
username = input("Enter your username: ")
password = input("Enter your password: ")

# Check username length
if len(username) < 5:
    print("Username is too short. It should be at least 5 characters long.")
else:
    # Check if the password contains the username
    if username in password:
        print("Password cannot contain the username.")
    else:
        # Check password length
        if len(password) < 8:
            print("Password is too short. It should be at least 8 characters long.")
        else:
            # Successful login
            print("You have logged in successfully!")

```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >We use the <code>input()</code> function to collect the user's username and password. We perform the checks as specified in the exercise, displaying the appropriate messages for each condition.
</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**

<h4 id="exercises" style="font-family: Georgia;">5. Write a Python program that asks the user to enter 5 names one by one and appends them to a list. After all the names have been entered, use a for loop to calculate and display the lengths of those names.</h4>  

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

```python
# Initialize an empty list to store names
names = []

# Ask the user to enter 5 names and append them to the list
for i in range(5):
    name = input(f"Enter name {i + 1}: ")
    names.append(name)

# Calculate and display the lengths of the entered names
name_lengths = []

for name in names:
    length = len(name)
    name_lengths.append(length)

print("Lengths of the entered names:")
for i, length in enumerate(name_lengths, start=1):
    print(f"Name {i}: {length} characters")

```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >We start with an empty list called <code>names</code>. </br> We use a for loop to ask the user to enter 5 names one by one, and we append each name to the names list. </br>After all names have been entered, we initialize an empty list called <code>name_lengths</code> .</br> We use another for loop to calculate the length of each name using the <code>len()</code> function and append those lengths to the <code>len()</code> list. </br> Finally, we display the lengths of the entered names with a message indicating which name corresponds to each length.
</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**


<h4 id="exercises" style="font-family: Georgia;">6. You are given a string containing words separated by spaces. Write a Python function called <code>reverse_words</code> that takes this string as input and returns the string with the words reversed.</h4>  

<h5 style="font-family: Georgia;">For example:</h5>

```yaml
Input: "Python is fun"
Output: "nohtyP si nuf"
```

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

```python
def reverse_words(input_string):
    # Split the input string into words using spaces as separators
    words = input_string.split()

    # Initialize an empty list to store reversed words
    reversed_words = []

    # Iterate through the words and reverse each word
    for word in words:
        reversed_word = word[::-1]  # Reverse the word using slicing
        reversed_words.append(reversed_word)

    # Join the reversed words with spaces to form the final string
    reversed_string = ' '.join(reversed_words)

    return reversed_string

# Test cases
input_str1 = "Hello World"
output1 = reverse_words(input_str1)
print(output1)  # Output: "olleH dlroW"

input_str2 = "Python is fun"
output2 = reverse_words(input_str2)
print(output2)  # Output: "nohtyP si nuf"
```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >The <code>reverse_words</code> function takes an input string containing words separated by spaces as an argument.

- It splits the input string into individual words by using the <code>split</code> method, which separates words based on spaces.

- An empty list <code>reversed_words</code> is created to store the reversed words.

- It then iterates through the list of words, reversing each word using slicing. The <code>slice [::-1]</code> reverses the characters in a string.

- The reversed words are added to the <code>reversed_words</code> list.

- Finally, the reversed words are joined back together into a single string with spaces using the <code>join</code>  \method.

- The reversed string is returned as the output of the function.
</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**



<h4 id="exercises" style="font-family: Georgia;">7. Suppose you are working in the finance department of a company, and you have a text file named <code>"salaries.txt" </code>that contains the monthly salaries of employees, one per line. Each salary is a whole number representing an employee's monthly earnings.</h4>  

<div style="font-family: Georgia;">
Write a Python function called  <code>calculate_total_salary</code> that reads the salaries from the file and calculates the total monthly salary expenses for the company. The function should return the total salary as an integer.

Additionally, create a new text file named <code>"expense_report.txt"</code> and write the calculated total salary to this file in a clear format.

Write the <code>calculate_total_salary</code> function and include the necessary code to perform the file reading and writing operations in the financial context.
</div>

<h5 style="font-family: Georgia;">salaries.txt</h5>

```yaml
5000
6000
4500
7000
```

<h5 style="font-family: Georgia;">expense_report.txt</h5>

```yaml
Total Monthly Salary Expense: $22500
```

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

```python
def calculate_total_salary():
    try:
        # Open the input file for reading
        with open("salaries.txt", "r") as file:
            # Read lines and convert them to integers, ignoring empty lines
            salaries = [int(line) for line in file if line.strip()]

        # Calculate the total salary expenses
        total_salary = sum(salaries)

        # Open the output file for writing
        with open("expense_report.txt", "w") as output_file:
            # Write the result to the output file
            output_file.write(f"Total Monthly Salary Expense: ${total_salary}")

        return total_salary

    except FileNotFoundError:
        return None  # Return None if the file is not found

# Call the function to calculate the total salary expense and write the result
total_salary = calculate_total_salary()

if total_salary is not None:
    print(f"Total Monthly Salary Expense: ${total_salary}")
    print("Expense report has been generated in 'expense_report.txt'")
else:
    print("Input file 'salaries.txt' not found.")

```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >The function <code>calculate_total_salary</code> is designed to work with salary data. It reads the monthly salaries of employees from the "salaries.txt" file, calculates the total salary expenses, and writes the result to the "expense_report.txt" file.

- The "salaries.txt" file is opened for reading, and salaries are extracted, converted to integers, and stored in the <code>salaries</code> list. Any empty lines or lines with only whitespace are ignored.

- The total salary expenses are calculated using the <code>sum</code> function.

- The "expense_report.txt" file is opened for writing, and the result is written in the format "Total Monthly Salary Expense: $total_salary."

- The function returns the total salary as an integer.

- The code calls the <code>calculate_total_salary</code> function, and if the result is not <code>None</code>, it prints the total salary expense and indicates that the expense report has been generated in "expense_report.txt." If the "salaries.txt" file is not found, it prints a message to that effect.
</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**



<h4 id="exercises" style="font-family: Georgia;">8. Your task is creating a Python program to manage a simple student database. Create a Python program that simulates a student database using a dictionary. The program should allow the user to perform the following operations:.</h4>  

<ol style="font-family: Tahoma;">
    <li><b>Add Student:</b> Add a student's name and their corresponding age to the database.</li>
    <li><b>Remove Student:</b> Remove a student from the database using their name.</li>
    <li><b>Search Student:</b> Search for a student by their name and display their age..</li>
    <li><b>Display Database:</b> Display the entire student database.</li>
</ol>

<div style="font-family: Georgia;">
You should implement these operations as a menu-driven program, where the user can choose to perform one of the above operations.

Here's an example of how the program should work:
</div>

```yaml
Student Database Menu:
1. Add Student
2. Remove Student
3. Search Student
4. Display Database
5. Quit

Select an option: 1
Enter student name: Ali
Enter student age: 20

Select an option: 1
Enter student name: Atilla
Enter student age: 22

Select an option: 4
Student Database:
Alice, Age: 20
Bob, Age: 22

Select an option: 2
Enter student name to remove: Ali

Select an option: 3
Enter student name to search: Atilla
Bob, Age: 22

Select an option: 5
Goodbye!


```

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

```python
student_database = {}

while True:
    print("Student Database Menu:")
    print("1. Add Student")
    print("2. Remove Student")
    print("3. Search Student")
    print("4. Display Database")
    print("5. Quit")
    
    option = input("Select an option: ")
    
    if option == "1":
        name = input("Enter student name: ")
        age = input("Enter student age: ")
        student_database[name] = age
    elif option == "2":
        name = input("Enter student name to remove: ")
        if name in student_database:
            del student_database[name]
    elif option == "3":
        name = input("Enter student name to search: ")
        if name in student_database:
            print(f"{name}, Age: {student_database[name]}")
        else:
            print("Student not found.")
    elif option == "4":
        print("Student Database:")
        for name, age in student_database.items():
            print(f"{name}, Age: {age}")
    elif option == "5":
        print("Goodbye!")
        break
```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >The program utilizes a <code>while</code> loop to create a menu-driven interface that remains active until the user decides to exit.
- A dictionary called `student_database` to store student names as keys and their corresponding ages as values.
- The program offers a menu of options, allowing the user to select the desired operation.
- Depending on the user's choice, the program carries out operations such as adding students, removing students, searching for students, displaying the database, or concluding the program.

</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**




<h4 id="exercises" style="font-family: Georgia;">9. Suppose you are working on a Python project and need to utilize a custom module named <code>"math_operations.py"</code> that contains various mathematical functions. The module provides functions for addition, subtraction, multiplication, and division of numbers. Your task is to create a Python program that uses this module to perform arithmetic operations on two numbers provided by the user..</h4>  

<ol style="font-family: Tahoma;">
    <li>Create a Python program that imports the "math_operations" module and the "numeric_input" module.</li>
    <li>The "numeric_input" module provides a function called get_numeric_input that ensures the user enters valid numeric input. Import and use this function to get two numeric inputs from the user.</li>
    <li>Display a menu to the user with options for addition, subtraction, multiplication, and division..</li>
    <li>Based on the user's choice, call the corresponding function from the "math_operations" module and display the result.</li>
    <li>Ensure that the program handles division by zero gracefully by displaying an appropriate message.</li>
</ol>

<div style="font-family: Georgia;">
You should implement these operations as a menu-driven program, where the user can choose to perform one of the above operations.

Here's an example of how the program should work:
</div>

```yaml
Enter the first number: 10
Enter the second number: 5

Select an operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division

Enter your choice (1/2/3/4): 3

Result: 50.0
```


<h4 style="font-family: Georgia;">Note:</h4>
<div style="font-family: Georgia;">
1) Ensure that division by zero is gracefully handled. </br>
2) The <code>"math_operations.py"</code> module contains functions named <code>add, subtract, multiply, and divide</code>  for performing the respective operations.</br>
3) The <code>"numeric_input"</code> module contains the <code>get_numeric_input</code> function for user input validation.
</div></br>

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

<h5 style="font-family: Georgia;">math_operations.py:</h5>

```python
# Function to add two numbers
def add(x, y):
    return x + y

# Function to subtract two numbers
def subtract(x, y):
    return x - y

# Function to multiply two numbers
def multiply(x, y):
    return x * y

# Function to divide two numbers
def divide(x, y):
    if y == 0:
        raise ValueError("Division by zero is not allowed.")
    return x / y
```

<h5 style="font-family: Georgia;">numeric_input.py:</h5>

```python
def get_numeric_input(prompt):
    while True:
        try:
            value = float(input(prompt))
            return value
        except ValueError:
            print("Invalid input. Please enter a numeric value.")
```

<h5 style="font-family: Georgia;">main.py:</h5>

```python
import math_operations
import numeric_input

if __name__ == "__main__":
    # Get user input for two numbers using the numeric_input module
    num1 = numeric_input.get_numeric_input("Enter the first number: ")
    num2 = numeric_input.get_numeric_input("Enter the second number: ")

    # Display a menu for operation selection
    print("\nSelect an operation:")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")

    # Get the user's choice
    choice = input("Enter your choice (1/2/3/4): ")

    # Perform the selected operation and display the result
    try:
        if choice == '1':
            result = math_operations.add(num1, num2)
            operation = "Addition"
        elif choice == '2':
            result = math_operations.subtract(num1, num2)
            operation = "Subtraction"
        elif choice == '3':
            result = math_operations.multiply(num1, num2)
            operation = "Multiplication"
        elif choice == '4':
            if num2 == 0:
                print("Error: Division by zero is not allowed.")
                result = None
            else:
                result = math_operations.divide(num1, num2)
                operation = "Division"
        else:
            print("Invalid choice. Please select 1, 2, 3, or 4.")
            result = None

        if result is not None:
            print(f"\nResult of {operation}: {result}")
    except ValueError as e:
        print(f"Error: {e}")

```


<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >The <code>"math_operations.py"</code> module is imported to access the mathematical functions such as addition, subtraction, multiplication, and division. These functions are defined in the module to perform corresponding arithmetic operations.

- The <code>"numeric_input"</code> module is imported to ensure that the user enters valid numeric input. The <code>get_numeric_input</code> function from this module validates user input, making sure it's a numeric value, and handles invalid input gracefully by displaying a message and prompting for input again.

- The main program interacts with the user to obtain two numeric values (numbers) using the <code>get_numeric_input</code> function. The user is prompted to enter the first and second numbers, ensuring that they are valid numeric inputs. This helps prevent errors due to non-numeric input.

- The program presents a menu to the user, displaying options for arithmetic operations. The user is prompted to choose from the following operations: addition, subtraction, multiplication, or division.

- Based on the user's choice, the program calls the corresponding function from the <code>"math_operations.py"</code> module. For example, if the user chooses addition, the add function is called, which takes the two numbers provided by the user and returns the result.

- The program ensures that division by zero is handled gracefully. If the user attempts division and the second number is zero, the program displays an error message to inform the user that division by zero is not allowed.

- Appropriate messages are displayed to the user throughout the program to provide feedback, such as displaying the result of the chosen operation or error messages in case of invalid input or division by zero.

</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**


<h4 id="exercises" style="font-family: Georgia;">10. You are working on a Pygame project that involves creating a basic interactive scene. Your goal is to add various elements to the Pygame window, including text, an image, and a background color. Follow these instructions to complete the task:</h4>  

<ol style="font-family: Tahoma;">
    <li>Create a Pygame program that opens a window, set background color,  displays an image, and shows text on the window.</li>
    <li>The Pygame library must be installed.</li>
    <li>The program should open a Pygame window with a specified width and height.</li>
    <li>Load and display an image (e.g., a PNG or JPG file) on the window.</li>
    <li>Set the background color of the window to a color of your choice.</li>
    <li>The program should display the window with the image and text for a specified duration.</li>
</ol>

<div style="font-family: Georgia;">

</div>



<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

<h5 style="font-family: Georgia;">math_operations.py:</h5>

```python
import pygame
import sys

# Initialize Pygame
pygame.init()

# Constants
WIDTH, HEIGHT = 800, 600
BACKGROUND_COLOR = (200, 200, 200)
TEXT_COLOR = (0, 0, 0)
IMAGE_PATH = "your_image.png"  # Replace with the path to your image
TEXT_MESSAGE = "Hello, Pygame!"
TEXT_FONT = "Arial"
TEXT_SIZE = 36
DISPLAY_DURATION = 5  # in seconds

# Create the game window
window = pygame.display.set_mode((WIDTH, HEIGHT))
pygame.display.set_caption("Image and Text Display")

# Load the image
image = pygame.image.load(IMAGE_PATH)

# Calculate image position
image_rect = image.get_rect()
image_x = (WIDTH - image_rect.width) // 2
image_y = (HEIGHT - image_rect.height) // 2

# Initialize the font
font = pygame.font.SysFont(TEXT_FONT, TEXT_SIZE)

# Calculate text position
text_surface = font.render(TEXT_MESSAGE, True, TEXT_COLOR)
text_x = (WIDTH - text_surface.get_width()) // 2
text_y = HEIGHT - 100

# Set the background color
window.fill(BACKGROUND_COLOR)

# Display the image and text
window.blit(image, (image_x, image_y))
window.blit(text_surface, (text_x, text_y))

# Update the display
pygame.display.flip()

# Display for a specified duration
pygame.time.delay(DISPLAY_DURATION * 1000)  # Convert seconds to milliseconds

# Quit Pygame
pygame.quit()
sys.exit()

```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >In this Pygame program, we create a window with a specified size and set a background color. We load and display an image at a particular position on the window and add text to it. The text and image are correctly positioned within the window. When the user clicks on the displayed image, the text message changes. The program also allows the user to exit the program gracefully.

</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**



<h4 id="exercises" style="font-family: Georgia;">11. Your task is creating a Python program to manage a vehicle inventory system. The system should allow you to add different types of vehicles,  including cars and motorcycles, to the inventory. Each vehicle has common properties such as a make, model, year, and price. Additionally, cars have unique properties such as the number of doors, and motorcycles have unique properties such as engine displacement.</h4>  

<ol style="font-family: Tahoma;">
    <li>
        <b>Step 1: </b> Create a Vehicle Class</br>
        Create a base class named Vehicle with the following properties:</br>
        make  ----> The make of the vehicle.</br>
        model ----> The model of the vehicle.</br>
        year ----> The manufacturing year of the vehicle.</br>
        price ----> The price of the vehicle.</br>
    </li>
    <li>
        <b>Step 2:</b> Implement Encapsulation </br>
        Use encapsulation to protect the properties of the Vehicle class. </br>
        Mark them as private attributes and provide getter and setter  </br>
        methods to access and modify these attributes.  </br>
    </li>
    <li>
        <b>Step 3: </b> Create Subclasses </br>
        Create two subclasses, Car and Motorcycle, which inherit from the Vehicle class.</br>
    </li>
    <li>
        <b>Step 4: </b> Implement Polymorphism</br>
        Override the __str__ method in both the Car and Motorcycle classes to provide a string representation of the vehicle.  </br>
       Include all relevant details such as make, model, year, price, and any unique properties. </br>
    </li>
     <li>
        <b>Step 5: </b> Add Unique Properties</br>
        In the Car class, add a property called num_doors (integer) to represent the number of doors in the car.</br>
        In the Motorcycle class, add a property called engine_displacement to represent the engine displacement.
    </li>
    <li>
        <b>Step 6: </b> Create an Inventory Class</br>
      Create a class named Inventory to manage the collection of vehicles.</br>
      Implement methods to add vehicles to the inventory, </br>
      list all vehicles, and calculate the total value of the inventory.
    </li>
      <li>
        <b>Step 7: </b> Example Usage</br>
        Create instances of cars and motorcycles.</br>
        Add them to the inventory using the Inventory class.</br>
        Display the details of vehicles in the inventory.</br>
        Calculate and display the total value of the inventory.
    </li>
</ol>

<h5 style="font-family: Georgia;">Step 7: </h5>

```python
 car1 = Car("Toyota", "Camry", 2022, 25000.0, 4)
 motorcycle1 = Motorcycle("Harley-Davidson", "Sportster", 2021, 12000.0, "1200cc")

 inventory = Inventory()
 inventory.add_vehicle(car1)
 inventory.add_vehicle(motorcycle1)

 inventory.list_vehicles()

 total_value = inventory.calculate_total_value()
 print("Total Inventory Value: $", total_value)
```


<details><summary><b style="font-family: Tahoma;">Answer</b></summary>

<p>

```python
# Step 1: Create a Vehicle Class
# Step 2: Implement Encapsulation
class Vehicle:
    def __init__(self, make, model, year, price):
        self.__make = make
        self.__model = model
        self.__year = year
        self.__price = price

    def get_make(self):
        return self.__make

    def set_make(self, make):
        self.__make = make

    def get_model(self):
        return self.__model

    def set_model(self, model):
        self.__model = model

    def get_year(self):
        return self.__year

    def set_year(self, year):
        self.__year = year

    def get_price(self):
        return self.__price

    def set_price(self, price):
        self.__price = price

    def __str__(self):
        return f"{self.__year} {self.__make} {self.__model} - ${self.__price:.2f}"

# Step 3: Create Subclasses (Car and Motorcycle)
# Step 4: Implement Polymorphism
# Step 5: Add Unique Properties
class Car(Vehicle):
    def __init__(self, make, model, year, price, num_doors):
        super().__init__(make, model, year, price)
        self.__num_doors = num_doors

    def get_num_doors(self):
        return self.__num_doors

    def set_num_doors(self, num_doors):
        self.__num_doors = num_doors

    def __str__(self):
        return super().__str__() + f", {self.__num_doors}-door"

class Motorcycle(Vehicle):
    def __init__(self, make, model, year, price, engine_displacement):
        super().__init__(make, model, year, price)
        self.__engine_displacement = engine_displacement

    def get_engine_displacement(self):
        return self.__engine_displacement

    def set_engine_displacement(self, engine_displacement):
        self.__engine_displacement = engine_displacement

    def __str__(self):
        return super().__str__() + f", {self.__engine_displacement} engine"

# Step 6: Create an Inventory Class
class Inventory:
    def __init__(self):
        self.__vehicles = []

    def add_vehicle(self, vehicle):
        self.__vehicles.append(vehicle)

    def list_vehicles(self):
        print("Inventory:")
        for vehicle in self.__vehicles:
            print(vehicle)

    def calculate_total_value(self):
        total_value = sum(vehicle.get_price() for vehicle in self.__vehicles)
        return total_value

# Example Usage
car1 = Car("Toyota", "Camry", 2022, 25000.0, 4)
motorcycle1 = Motorcycle("Harley-Davidson", "Sportster", 2021, 12000.0, "1200cc")

inventory = Inventory()
inventory.add_vehicle(car1)
inventory.add_vehicle(motorcycle1)

inventory.list_vehicles()

total_value = inventory.calculate_total_value()
print("Total Inventory Value: $", total_value)


```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >In this Pygame program, we create a window with a specified size and set a background color. We load and display an image at a particular position on the window and add text to it. The text and image are correctly positioned within the window. When the user clicks on the displayed image, the text message changes. The program also allows the user to exit the program gracefully.

</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**


<h4 id="exercises" style="font-family: Georgia;">12. You are given a string that contains text with multiple sentences. Your task is to create a Python program that performs various operations on this string without using external libraries. The operations are as follows:</h4>  
<ol style="font-family: Tahoma;">
  <li><b>Sentence Count:</b>Calculate and display the total number of sentences in the given string. Sentences are defined by periods ('.'), exclamation marks ('!'), or question marks ('?').</li>
  <li><b>Word Count:</b> Calculate and display the total number of words in the string. Words are defined as sequences of characters separated by spaces or punctuation.</li>

  <li><b>Longest Sentence: </b>Find and display the longest sentence in terms of the number of words. If there are multiple sentences with the same maximum word count, display the first one.</li>

  <li><b>Shortest Sentence:</b> Find and display the shortest sentence in terms of the number of words. If there are multiple sentences with the same minimum word count, display the first one.</li>
  <li><b>Word Frequency: </b> Calculate and display the frequency of each unique word in the string, sorted by frequency in descending order. Ignore punctuation and consider words in a case-insensitive manner. If there are multiple words with the same frequency, sort them alphabetically.</li>
</ol>


<h5 style="font-family: Georgia;">Input:</h5>

```yaml
sentencet: "This is a string exercise, and it's designed to be solvable without external libraries! With a little practice and determination, you can succeed. Success is achievable."
```

<h5 style="font-family: Georgia;">Output:</h5>

```yaml
Sentence Count: 3
Word Count: 26
Longest Sentence: This is a string exercise, and it's designed to be solvable without external libraries!
Shortest Sentence: Success is achievable
Word Frequency:
  a: 2
  and: 2
  is: 2
  achievable: 1
  be: 1
  can: 1
  designed: 1
  determination: 1
  external: 1
  its: 1
  libraries: 1
  little: 1
  practice: 1
  exercise: 1
  solvable: 1
  string: 1
  succeed: 1
  success: 1
  this: 1
  to: 1
  with: 1
  without: 1
  you: 1


```

<details><summary><b style="font-family: Tahoma;">Answer</b></summary>
<p>

```python
# Input text
text = "This is a string exercise, and it's designed to be solvable without external libraries! With a little practice and determination, you can succeed. Success is achievable."

# Define sentence delimiters
sentence_delimiters = ['.', '!', '?']

# Initialize variables for sentences
sentences = []
current_sentence = ""

# Iterate through the characters in the text
for char in text:
    current_sentence += char
    if char in sentence_delimiters:
        sentences.append(current_sentence)
        current_sentence = ""

# Ensure the last sentence is added if the text doesn't end with a sentence delimiter
if current_sentence:
    sentences.append(current_sentence)

# Remove leading and trailing spaces in each sentence
sentences = [sentence.strip() for sentence in sentences if sentence.strip()]

# Calculate the total number of sentences
sentence_count = len(sentences)

# Initialize variables for the longest and shortest sentences
longest_sentence = ""
shortest_sentence = None

# Initialize a dictionary to store word frequencies
word_freq = {}

# Iterate through the sentences
for sentence in sentences:
    # Split the sentence into words
    words = sentence.split()
    
    # Update the longest and shortest sentences
    if not longest_sentence or len(words) > len(longest_sentence.split()):
        longest_sentence = sentence
    if not shortest_sentence or len(words) < len(shortest_sentence.split()):
        shortest_sentence = sentence

    # Update word frequencies
    for word in words:
        # Remove punctuation and make words lowercase
        word = ''.join(c for c in word if c.isalnum()).lower()
        if word:
            if word not in word_freq:
                word_freq[word] = 1
            else:
                word_freq[word] += 1

# Calculate the total number of words
total_words = sum(len(sentence.split()) for sentence in sentences)

# Sort word frequencies by frequency in descending order and then alphabetically
sorted_word_freq = sorted(word_freq.items(), key=lambda x: (-x[1], x[0]))

# Display the results
print("Sentence Count:", sentence_count)
print("Word Count:", total_words)
print("Longest Sentence:", longest_sentence)
print("Shortest Sentence:", shortest_sentence)
print("Word Frequency:")
for word, freq in sorted_word_freq:
    print(f"{word}: {freq}")

```

<span style="font-family: Tahoma;">Explanation:</span>

- <article style="font-family: Tahoma;" >We use string splitting to count sentences and words.
- To find the longest and shortest sentences, we use custom functions that count words in each sentence.
- We calculate word frequencies and sort them by frequency and alphabetically.
</article>
</p>
</details>

---

**[⬆ Back to Top](#exercises)**
