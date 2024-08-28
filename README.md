RandomNameGenerator

A Java application that generates randomized sequences of names and writes them to a file.
Overview

RandomNameGenerator is a straightforward Java program that takes a predefined list of names, shuffles them, and writes randomized sequences to a file. The generated sequences can be useful for various purposes, such as creating randomized lists or testing.
Features

    Randomization: Shuffles a list of names to create varied sequences.
    File Output: Writes the shuffled sequences to a file named names.dat.
    Reusability: The file is appended with new data each time the program runs.

Getting Started

To use the RandomNameGenerator, follow these steps:
Prerequisites

    Java Development Kit (JDK): Ensure you have JDK 8 or higher installed on your system.
    IDE or Command Line: You can use an IDE like IntelliJ IDEA, Eclipse, or compile and run the program from the command line.

Installation

    Clone the Repository

    bash

git clone https://github.com/yourusername/RandomNameGenerator.git

Navigate to the Project Directory

bash

cd RandomNameGenerator

Compile the Code

bash

javac NameGenerator.java

Run the Program

bash

    java NameGenerator

Configuration

    Names List: Modify the peoples array in NameGenerator.java to include any names you want to shuffle.
    Output File: The program appends the shuffled names to names.dat in the project directory. You can change the filename in the FileWriter constructor if needed.

Usage

When you run the program, it will:

    Shuffle the list of names.
    Write the shuffled names to names.dat, each sequence on a new line.
    Repeat this process 10 times, appending new sequences to the file.

Example Output

python

Alice Mike Bob Steve Ted Carol Amanda Danielle Elizabeth Howard Paige Sam Robert 
Sam Paige Ted Alice Howard Mike Steve Carol Bob Amanda Elizabeth Danielle Robert 
...
