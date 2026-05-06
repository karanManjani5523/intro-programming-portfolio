--Switch Statement

1) Concept in my own words:

A switch statement is used when we have many possible choices for one variable.
It is easier to read than many if-else statements.
The switch checks the value and matches it with a case.
The switch expression is evaluated once
The value of the expression is compared with the values of each case
If there is a match, the associated block of code is executed
The break and default keywords will be described later in this chapter

2) C# Syntax

int day = 2;
switch (day)
{
    case 1:
      Console.WriteLine("Monday");
      break;
    case 2:
      Console.WritEline("Tuesday"):
      break;
    default:
      Console.Writeline("Invalid Day"):
      break;
}

3) Eureka Exercise

I understood switch better when I made a day-of-week program.
It showed me how one value can have many possible results.

4) Common Mistake

I sometimes forget to write break after each case.
Without break, the switch can continue incorrectly.

5) Research References

Class Notes and W3 School Website
