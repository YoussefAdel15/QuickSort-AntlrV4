# QuickSort-AntlrV4
This repository contains an implementation of the QuickSort algorithm using the AntlrV4 parser generator tool.

# Description
The QuickSort algorithm is a sorting algorithm that works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays, according to whether they are less than or greater than the pivot. The sub-arrays are then recursively sorted.
<br />
This implementation uses AntlrV4 to parse a list of integers from a text file, and then sorts the integers using the QuickSort algorithm.
<br />
This Project Use BNF And You Can Explore it [here](https://www.cambridge.org/resources/052182060X/MCIIJ2e/grammar.htm)

## Getting Started
To run this program, you will need to have the AntlrV4 tool installed on your system. For instructions on installing AntlrV4, click [here](https://www.antlr.org/).
.

Once AntlrV4 is installed, clone this repository and run the following command to generate the parser:

```
antlr4 QuickSort.g4
```
This will generate the necessary Java files for parsing the input file.

To run the program, compile the Java files and run the QuickSort class with the input file as an argument:
```
javac QuickSort*.java
java QuickSort input.txt
```
Replace input.txt with the path to your input file.

## Another Way To Get Start

- You can Install Antlr plugin on intellij
- clone the project to your PC
- open the file (Project.g4) in intellij
- Right Click on goal and select (Test Rule goal) - This will open Antlr Test Window
- Put the Mini Java Code For Test Code Click [Here](https://www.cambridge.org/resources/052182060X/MCIIJ2e/programs/QuickSort.java)
- This Will Generate The Parsing Tree For The Code

### Input Format
The input file should contain a list of integers separated by whitespace. For example:

```
3 1 4 1 5 9 2 6 5 3 5
```
### Output Format
The program will output the sorted list of integers to the console, separated by whitespace. For example:

```
1 1 2 3 3 4 5 5 5 6 9
```
<br />
<br />
<br />

This Project Was Created As CS407 Final Project And You Can see the presentation [here](https://www.canva.com/design/DAFijw1akMs/S5DWyMlLH6U9lm8YJTZcSA/view?utm_content=DAFijw1akMs&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink#17)
