# Airthmatic-operator-using-method

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp43
{
    class calculation
    {
        public int add(int x,int y)
        {
            int sum = x + y;
            return sum;
        }
        public int sub(int x, int y)
        {
            int subtract = x - y;
            return subtract;
        }
        public int mul(int x, int y)
        {
            int multiplication = x * y;
            return multiplication;
        }
        public int div(int x, int y)
        {
            int division = x / y;
            return division;
        }
        static void Main(string[] args)
        {
            calculation obj = new calculation();
         
            Console.WriteLine("The sum of Numbers is:= " + obj.add(25, 25));
            Console.WriteLine("The sub of Numbers is:= " + obj.sub(100, 50));
            Console.WriteLine("The mul of Numbers is:= " + obj.mul(25, 5));
            Console.WriteLine("The div of Numbers is:= " + obj.div(78, 12));
            Console.ReadLine();
        }  

    }
}
