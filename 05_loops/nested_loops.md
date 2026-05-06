--Nested Loops

1) Concept in my own words:

Nested loops are loops inside another loop.
The outer loop controls the rows or main repetitions.
The inner loop runs completely every time the outer loop runs once.
Nested loops are useful for patterns, tables, and grids.
At first, they are confusing because there are two loop variables.
I learned that tracing step by step makes nested loops easier.
This concept is important for 2D arrays and pattern questions.

2) C# Syntax

for (int i = 1; i <= 3; i++)
{
    for (int j = 1; j <= 3; j++)
    {
        Console.Write(j);
    }
   Console.Writeline();
}

3) Eureka Exercise

I understood nested loops when I practiced printing square patterns.
I realized the outer loop controls lines and the inner loop controls columns.

4) Common Mistake

I sometimes confuse i and j.
This gives wrong output in patterns.

5) Research References

Class Notes and W3 School Website
