--Do While Loop

1) Concept in my own words:

A do-while loop is used to repeat code.
The special thing about do-while is that it runs at least one time.
After running once, it checks the condition.
If the condition is true, it repeats.
If the condition is false, it stops.
This loop is useful for input validation and menus.
I learned that do-while is good when the user must enter something at least once.

2) C# Syntax

int number;

do
{
    Console.Write("Enter a positive number: ");
    number = Convert.ToInt32(Console.ReadLine());
}
while (number <= 0);

3) Eureka Exercise

I understood do-while when I practiced validating user input.
It made sense because the program asks first and checks after.

4) Common Mistake

I sometimes forget the semicolon after while condition.
In do-while, the ending while line needs a semicolon.

5) Research References

Class Notes and W3 School Website
