--2D Arrays

1) Concept in my own words:

A 2D array stores values in rows and columns.
It works like a table or grid.
Each value is accessed using two indexes.
The first index is for the row and the second index is for the column.
2D arrays are useful for matrices, boards, and tables.
I learned that nested loops are usually used with 2D arrays.
This concept is important for organizing data in table form.

2) C# Syntax

int[,] numbers = new int[2, 2];

numbers[0, 0] = 1;
numbers[0, 1] = 2;
numbers[1, 0] = 3;
numbers[1, 1] = 4;

Console.WriteLine(numbers[1, 1]);

3) Eureka Exercise

I understood 2D arrays when I drew rows and columns on paper.
It helped me see how indexes work.

4) Common Mistake

I sometimes write numbers[0][1], but in C# 2D arrays use numbers[0, 1].

5) Research References

Class Notes and W3 School Website
