<h3 style="font-family: Tahoma; text-align:center;">Python Coding Exercises</h3>  

<p style="font-family: Tahoma; text-align:center;">Sharpen Your Coding Skills with Challenging Exercises</p>  

<article style="font-family: Tahoma;">
 Welcome to our coding exercises repository! Whether you're preparing for technical interviews, looking to enhance your programming skills, or simply enjoy solving coding challenges, you've come to the right place. In this README file, you'll find a curated collection of coding exercises covering <b style="color: crimson;">Python </b> programming language, data structures, algorithms, and real-world scenarios. Each exercise helping you understand the underlying concepts and improve your problem-solving abilities. Explore our collection, test your knowledge, and elevate your coding prowess!
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



---

**[⬆ Back to Top](#exercises)**




<h4 id="exercises" style="font-family: Georgia  ;">2. Using a single <code>print</code> statement and a format with asterisks and spaces, how can you create following shapes in Python?</h4>  

                          *               * * *
                         * *              *   *
                        * * *             * * *



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



---

**[⬆ Back to Top](#exercises)**


<h4 id="exercises" style="font-family: Georgia;">4. Your task is creating a basic Canvas login simulation program in Python. The program should prompt the user to enter their username and password using two different inputs. You need to perform the following checks:</h4>  
<ol style="font-family: Tahoma;">
  <li>Check if the username is less than 5 characters. If it is, display a message indicating that the username is too short.</li>
  <li>Check if the password contains the username. If it does, display a message indicating that the password cannot contain the username.</li>
  <li>Check if the password is less than 8 characters. If it is, display a message indicating that the password is too short.</li>
  <li>If all checks pass, display a message indicating that the user has logged in successfully.</li>

</ol>



---

**[⬆ Back to Top](#exercises)**

<h4 id="exercises" style="font-family: Georgia;">5. Write a Python program that asks the user to enter 5 names one by one and appends them to a list. After all the names have been entered, use a for loop to calculate and display the lengths of those names.</h4>  



---

**[⬆ Back to Top](#exercises)**


<h4 id="exercises" style="font-family: Georgia;">6. You are given a string containing words separated by spaces. Write a Python function called <code>reverse_words</code> that takes this string as input and returns the string with the words reversed.</h4>  

<h5 style="font-family: Georgia;">For example:</h5>

```yaml
Input: "Python is fun"
Output: "nohtyP si nuf"
```



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



---

**[⬆ Back to Top](#exercises)**
