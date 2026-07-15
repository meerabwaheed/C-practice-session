//here this practice we use for loop
using System;


using System;
//here is the even & odd number practice
class Program
{
    static void Main()
    {
        Console.Write("Enter a number: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 2 == 0)
        {
            Console.WriteLine("Even Number");
        }
        else
        {
            Console.WriteLine("Odd Number");
        }
    }
}
using System;

class Program
{
    static void Main()
    {
        Console.Write("Enter first number: ");
        int a = int.Parse(Console.ReadLine());

        Console.Write("Enter second number: ");
        int b = int.Parse(Console.ReadLine());

        if (a > b)
        {
            Console.WriteLine(a + " is greater");
        }
        else
        {
            Console.WriteLine(b + " is greater");
        }
    }
}
using System;

class Program
{
    static void Main()
    {
        Console.Write("Enter a number: ");
        int num = int.Parse(Console.ReadLine());

        for (int i = 1; i <= 10; i++)
        {
            Console.WriteLine(num + " x " + i + " = " + (num * i));
        }
    }
}
using System;

class Program
{
    static void Main()
    {
        Console.Write("Enter a number: ");
        int num = int.Parse(Console.ReadLine());

        int fact = 1;

        for (int i = 1; i <= num; i++)
        {
            fact = fact * i;
        }

        Console.WriteLine("Factorial = " + fact);
    }
}
🧪 Practice Task
Write a program that:

Creates an array of 5 integers.

Takes input from the user for each index.

Prints all the elements.

Prints only the even numbers from the array.

    */
    static void Main()
    {
        int[] numbers = new int[5];
        for (int i = 0; i < numbers.Length; i++)
        {
            Console.WriteLine("Enter a Number for index " + i + " :");
            string enteredNumber = Console.ReadLine();
            numbers[i] = Convert.ToInt32(enteredNumber);
        }
        // printing the arrays indexes
        for (int i = 0; i < numbers.Length; i++)
        {
            Console.WriteLine("index " + i + " : " + numbers[i]);
        }
        Console.WriteLine("\nEven numbers:");
        foreach (int number in numbers)
        {
            if (number % 2 == 0)
            {
                Console.WriteLine("Even numbers " + number);
            }
        }
    }

}
using System;
class Program
{
/_
Create an array of 5 integers.
Ask the user to enter 5 numbers (use a loop).
Print all the entered numbers
Find and print:
The maximum number in the array.
The minimum number in the array.
_/
static void Main()
{
int[] numbers = new int[5];
int max = numbers[0];
int min = numbers[0];
for (int i = 0; i < numbers.Length; i++)
{
Console.WriteLine("Enter the number for index " + i);
string enteredNumber = Console.ReadLine();
numbers[i] = Convert.ToInt32(enteredNumber);
// Console.WriteLine(enteredNumber);

    	}
    	// printing all the indexes taken from the user
    	for (int i = 0; i < numbers.Length; i++)
    	{
    		Console.WriteLine("The number entered by user at index " + i + " is :" + numbers[i]);
    	}

    	for (int i = 0; i < numbers.Length; i++)
    	{
    		if (numbers[i] > max)
    		{
    			max = numbers[i];
    		}
    		if (numbers[i] < min)
    		{
    			max = numbers[i];
    		}
    	}

    	Console.WriteLine("max: " + max);
    	Console.WriteLine("min: " + min);

    }

}
using System;
class Program
{
/_
🔧 Instructions:
Create an array of 7 integers.
Take 7 numbers as input from the user.
Count:
How many are positive (> 0)
How many are negative (< 0)
How many are zero (== 0)
Print the counts.//Take two numbers and print their sum.
using System;
class Program {
    static void Main(string[] args)
    {
        Console.Write("Enter First number:");
        int num1 = int.Parse(Console.ReadLine());

        Console.Write("Enter Second number:");
        int num2 = int.Parse(Console.ReadLine());

        int sum = num1 + num2;

        Console.WriteLine("sum" + sum);
    }
}
//2.Check if User is Eligible for Voting

using System;
class Program {
    static void Main(string[] args)
    {
        Console.Write("Enter your age:");
        int age = int.Parse(Console.ReadLine());

        if(age >= 18)
        {
            Console.WriteLine("you are Elligible for vote");
        }
        else
        {
            Console.WriteLine("Your are not Elligible for vote");

        }
    }
}
//Print numbers from 1 to 100 using a loop.
using System;
class Program
{
    static void Main(string[] args)
    {
        for(int i = 1; i <= 100; i++)
        {
            Console.WriteLine(i);
        }
    }
}

//Store 5 marks in an array and print them.
using System;
class Program {
    static void Main(string[] args)
    {
        int[] marks = new int[5] ;
        Console.WriteLine("Enter 5 marks");

        for(int i = 1; i<= marks.Length; i++)
        {
            marks[i] = int.Parse(Console.ReadLine());
        }
        Console.WriteLine("Marks are:");

        for (int i = 0; i < 5; i++)
        {
            Console.WriteLine(marks[i]);
        }
    }

}
