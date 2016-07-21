Game: Rock, Paper and Scissors
I propose a schematic analysis of the game in object of this technical test:
Problem to resolve
Write a program that plays 100 iterations of Rock, Paper, Scissors 
One player → play randomly
Second player → always play rock
The program have to show at the end how many games each player has one
and how many were a draw.
Type of solution 
Shapes: Rock = 0, Paper = 1 and Scissors=2
Core of the algorithm is given by a note:
The moves are in a cycle. In order to determinate the winner the follow 
mathematical formula is useful:
x = (n + a - b) % n 
where 
n = number of total shapes 
a = first shape (by ordinal code)
b = second shape (by ordinal code)
2.  Assumptions
Programming Language
Java 7
Frameworks used
Junit v4
Methodology of the code development
Test Driven Development
UML Diagrams 
Not required → Not implemented
i18n international messages
Messages.properties
Error logs
Slf4j library
Java Docs
Available but not compiled
