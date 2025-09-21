# WEATHERDATASYSTEM
Weather Data Management System (C++)
📌 Overview

This project is a C++ console-based Weather Data Storage System that manages temperature records for multiple cities across different years.
It demonstrates the use of 2D arrays (years × cities), row-major and column-major traversal, and sparse data handling.

🚀 Features

Insert Records: Add temperature data for a city in a given year.

Delete Records: Remove stored weather data.

Retrieve Data: Display all available records for a particular city.

Row-Major Traversal: View stored data row by row (years).

Column-Major Traversal: View stored data column by column (cities).

Sparse Data Handling: Print only non-empty entries, ignoring missing data.

Complexity Analysis: Outputs time and space complexity of each operation.

🛠️ Technologies Used

Language: C++ (C++11 or later)

Compiler: g++ / MSVC / Clang

📂 Project Structure
weather_data_system.cpp   # Main program (all logic + driver code)
README.md                 # Documentation

⚙️ Compilation & Execution

Open a terminal and navigate to the project folder.

Compile the program:

g++ weather_data_system.cpp -o weather_data


Run the program:

./weather_data
