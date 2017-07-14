# Count-the-Integers
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Count_the_Integers
{
    class Program
    {
        static void Main(string[] args)
        {
            int count = 0;
            try
            {
            int num = int.Parse(Console.ReadLine());
                while (true)
                {
                    count++;
                    num = int.Parse(Console.ReadLine());
                }
            }
            catch 
            {
                Console.WriteLine(count);
            }

        }
    }
}
