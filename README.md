# kodluyoruzdokuzuncurepo
if else if
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace HackerRank2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Lütfen bir sayı giriniz");
            int N = Convert.ToInt32(Console.ReadLine().Trim());

            if (N % 2 != 0)
            {
                Console.WriteLine("Weird");
            }
            else if (N % 2 == 0 && N >= 2 && N <= 5)
            {
                Console.WriteLine("Not Weird");
            }
            else if (N % 2 == 0 && N >= 6 && N <= 20)
            {
                Console.WriteLine("Weird");
            }
            else
            {
                Console.WriteLine("Not Weird");
            }
            Console.ReadLine();
        }

    }
}
