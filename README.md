# Denominator
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Denominator
{
    class Program
    {
        static void Main(string[] args)
        {

            int devisor;
            devisor = Convert.ToInt32(Console.ReadLine());

            string str="";
            for (int i = 1; i<= devisor; i++)
            {
                if ((devisor % i) == 0)
                    str  += i.ToString() + "  ";
                    
            }
            Console.WriteLine(str);
            Console.ReadKey();

        }
    }
}
