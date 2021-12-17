# seif ahmed
04arrays

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _04ArraysEx
{
    class Program
    {
        static void Main(string[] args)
        {
            int []numbers = new int[20];
            Console.WriteLine("Enter 20 numbers: ");
            for (int i = 0; i < 20; i ++)
            {
                Console.Write("\nEnter number {0}: ", i+1);
                numbers[i] = int.Parse(Console.ReadLine());
            }
            Console.WriteLine("Reversed numbers: ");
            for(int i = 0; i < 20 ; i++)
            {
                Console.WriteLine("Number {0}: {1}", i+1, numbers[20 - i - 1]);
            }
        }
    }
}

