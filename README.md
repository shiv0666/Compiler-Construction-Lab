🧠 Compiler Construction Lab
This repository contains the practical assignments for the Compiler Construction Laboratory, covering key concepts of lexical analysis, syntax analysis, parsing, and intermediate code generation.
Each program demonstrates a fundamental aspect of compiler design and implementation using C/C++ and related tools.

📚 List of Practicals
Theory Assignment:
Write detailed notes on LEX and YACC Compilation Process — explain their structure, working, and importance in compiler design. (CO2)

Program 2 – Lexical Analysis:
Count the number of comments, keywords, identifiers, words, lines, and spaces from an input file. (CO1)

Program 3 – String Pattern Matching:
Count the number of words starting with the letter ‘A’. (CO3)

Program 4 – Case Conversion:
Convert all lowercase letters to uppercase and vice versa in a given file. (CO1)

Program 5 – Decimal to Hexadecimal Conversion:
Read a decimal number from a file and convert it to its hexadecimal equivalent. (CO1)

Program 6 – Line Testing:
Display all lines ending with “.COM” from the given input file. (CO3, CO5)

Program 7 – Postfix Expression Evaluation:
Implement a program to evaluate a postfix expression. (CO2)

Program 8 – Desk Calculator with Error Recovery:
Develop a simple calculator capable of performing arithmetic operations with error detection and recovery. (CO3, CO5)

Program 9 – Parser for “FOR” Loop:
Write a parser to recognize and validate the syntax of a FOR loop statement. (CO1, CO5)

Program 10 – Intermediate Code Generation:
Generate Intermediate Code (IC) for an Arithmetic Expression using standard compiler design techniques. (CO4)

🛠️ Tools and Technologies
Language: C / C++

Tools: LEX, YACC / Bison, GCC

Platform: Linux / Ubuntu / Windows (with MinGW)

Editor: VS Code / Turbo C / Code::Blocks

🚀 How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/<your-username>/compiler-construction-lab.git
Navigate to the desired practical folder:

bash
Copy code
cd Practical-1
Compile and run:

bash
Copy code
lex filename.l
yacc -d filename.y
gcc lex.yy.c y.tab.c -o output
./output
🧩 Learning Outcomes
Understand the working of lexical and syntax analyzers.

Implement token recognition and parsing techniques.

Develop basic understanding of intermediate code generation.

Explore error handling and recovery in compilers.

👨‍💻 Author
Name: Shivansh Lohani
Course: Compiler Construction Lab
Institute: SIT NAgpur
Year: 2025

