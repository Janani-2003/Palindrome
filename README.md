# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step 1: To start the C# program in visual Studio 2022.

Step 2: Create a class and declare two variable with string datatype.

Step 3: Loop over the entire string and reverse it.

Step 4: Use if condition to check whether the string and the reversed string is equal or not.

Step 5: print palindrome if it's equal else print not a palindrome.

Step 6: Save the program and run the program in visual studio 2022.

## Program:
```
using System;
class HelloWorld
{
    static void Main()
    {
        string num1, rem, rev = "";
        Console.Write("Enter a string : ");
        num1 = Console.ReadLine();
        rem = num1;
        for (int s = num1.Length - 1; s >= 0; s--)
        {
            rev += num1[s];
        }
        Console.WriteLine(rev);
        if (rev == rem)
            Console.WriteLine(rem + " is a palindrome");
        else
            Console.WriteLine(rem + " is not a palindrome");

    }
}
```
## Output:
![Screenshot 2023-03-17 160749](https://user-images.githubusercontent.com/94288340/225882053-6e79197b-cd59-4656-aa8d-08e6566901f3.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
