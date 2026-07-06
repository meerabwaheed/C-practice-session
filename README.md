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
