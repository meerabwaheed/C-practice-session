//here this practice we use for loop
using System;

class Program
{
    static void Main()
    {
        for (int i = 1; i <= 100; i++)
        {
            Console.WriteLine(i);
        }
    }
}
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
