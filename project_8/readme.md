# 📌 About the Project

NumPy Array Analyzer is a menu-driven Python application built using the powerful NumPy library. It allows users to create arrays and perform a variety of mathematical, array manipulation, searching, sorting, filtering, and statistical operations through a simple interactive command-line interface.

This project is designed to strengthen Python programming skills, object-oriented programming (OOP), and practical understanding of NumPy arrays.

Whether you're learning Python or exploring numerical computing, this project provides a hands-on introduction to working with arrays efficiently.

✨ Features
Feature Description
🔢 Array Creation Create 1D and 2D arrays using user input
➕ Mathematical Operations Perform addition, subtraction, multiplication, and division
🔗 Array Combination Combine arrays horizontally or vertically
✂️ Array Splitting Split an array into multiple parts
🔍 Array Searching Find the positions of a specified value
📊 Array Sorting Sort array elements row-wise or column-wise
🎯 Array Filtering Filter elements greater than a specified value
🧮 Aggregation Calculate the sum, minimum, and maximum
📈 Statistics Calculate mean, median, standard deviation, and variance
🔄 Interactive Menus Navigate between operations using menu choices
🛠️ Technologies Used
Python 3 — Core programming language
NumPy — Numerical computing and array manipulation
Object-Oriented Programming — Organizes operations inside the Analyzer class
Command-Line Interface (CLI) — Provides interactive menu-based navigation
📂 Project Structure
text
NumPy-Array-Analyzer/
│
├── analyzer.py       # Main Python application
├── README.md         # Project documentation
└── requirements.txt  # Project dependencies (optional)

Note: analyzer.py is a suggested filename. Rename it to match your actual Python file.

⚙️ Installation & Setup

1. Clone the repository
bash

1. Navigate to the project directory
bash
cd YOUR-REPOSITORY

1. Install NumPy
bash
python -m pip install numpy

1. Run the program
bash
python analyzer.py

If your Python installation uses python3, run:

bash
python3 analyzer.py

🎮 How to Use

After launching the program, you will see the main menu:

text
Welcome to our new project Analyzer :)
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

Enter 1 to Create Numpy Array.
Enter 2 to Perform Mathematical Operations on Array.
Enter 3 to Combine Or Split Array.
Enter 4 to Search,Sort and Filter Array.
Enter 5 to Compute Aggregates Or Statistics.
Enter 0 to exit the programme.

Choose an option by entering its corresponding number.

🔢 1. Create NumPy Array
Create a one-dimensional array.
Create a two-dimensional array by specifying rows, columns, and elements.

Example:

text
Enter the number of rows: 2
Enter the number of Column: 3
Enter the 6 Elements for Array separated by ',': 1,2,3,4,5,6

Output:

text
[[1 2 3]
 [4 5 6]]

➕ 2. Mathematical Operations

Perform element-wise mathematical operations on two arrays of the same shape.

Addition
Subtraction
Multiplication
Division

Example:

Array A:

text
[[1 2]
 [3 4]]

Array B:

text
[[5 6]
 [7 8]]

Addition result:

text
[[ 6  8]
 [10 12]]

🔗 3. Combine or Split Arrays

Combine compatible arrays using:

np.hstack() — Horizontal combination
np.vstack() — Vertical combination

Split arrays using:

np.split() — Divide an array into equal sections

Important: Horizontal combination requires matching row counts, while vertical combination requires matching column counts. Splitting into equal sections also requires a compatible array dimension.

🔍 4. Search, Sort & Filter

Search for values, arrange array elements, and filter elements based on conditions.

np.where() — Find matching element positions
np.sort() — Sort elements along a selected axis
Boolean indexing — Select elements satisfying a condition

Example:

python
import numpy as np

arr = np.array([[8, 3, 6],
                [2, 9, 4]])

print(arr[arr > 5])

Output:

text
[8 6 9]

📊 5. Aggregates & Statistics

The program supports the following statistical calculations:

Operation NumPy Function
Sum np.sum()
Mean np.mean()
Median np.median()
Standard Deviation np.std()
Variance np.var()
Minimum np.min()
Maximum np.max()

These operations help summarize numerical data and understand its basic statistical properties.

🎥 Video Explanation

Watch the project demonstration and explanation here:

The video can cover:

Project introduction and objectives
Code structure and the Analyzer class
Creating 1D and 2D NumPy arrays
Performing mathematical operations
Combining and splitting arrays
Searching, sorting, and filtering
Computing aggregate values and statistics
Running the application with sample inputs

Note: Replace YOUR-YOUTUBE-VIDEO-LINK with your actual YouTube video URL before publishing the README.

🎯 Learning Objectives

By building this project, you can practice:

Python classes, objects, and methods
Loops and conditional statements
User input and interactive menus
NumPy array creation and reshaping
Array arithmetic and manipulation
Boolean indexing and searching
Basic statistical analysis
Input validation and error handling
🚀 Future Improvements

Possible enhancements for future versions include:

Add exception handling for invalid user inputs.
Prevent mathematical operations before arrays have been created.
Validate array dimensions before combining or splitting.
Handle division by zero.
Support floating-point array elements.
Add more advanced statistical operations.
Allow users to save and load arrays from files.
Improve the interface with a graphical user interface (GUI).
🤝 Contributing

Contributions, suggestions, and improvements are welcome!

Fork the repository.
Create a new branch for your feature.
Commit your changes.
Open a pull request describing your improvements.
📜 License

This project can be distributed under the MIT License. If you choose this license, add a LICENSE file containing the appropriate MIT License text.
