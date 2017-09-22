# Lab 1
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace lab1._1
{
    class Program
    {
        static void Main(string[] args)
        {
            string buf;
            Console.WriteLine("Введите alfa");
            buf = Console.ReadLine();
            double a = double.Parse(buf);
            double z1 = Math.Cos(a) + Math.Sin(a) + Math.Cos(3 * a) + Math.Sin(3 * a);
            double z2 = 2 * Math.Sqrt(2) * Math.Cos(a) * Math.Sin(Math.PI / 4 + 2 * a);
            Console.WriteLine("z1={0,6:f3}", z1);
            Console.WriteLine("z2={0,6:f3}", z2);
            Console.ReadKey();
        }
    }
}

