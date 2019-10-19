# zadachi


using System;

namespace grade
{
    class Program
    {
        static void Main(string[] args)
        {
            double grade = double.Parse(Console.ReadLine());
            if (grade >= 5.50)
            {
                Console.WriteLine(" Excellent ");
            }

            else if (grade >= 4.50)
            {
                Console.WriteLine(" Very Good ");
            }

            else if (grade >= 3.50)
            {
                Console.WriteLine(" Good ");
            }

            else if (grade >= 2.50)
            {
                Console.WriteLine(" Medium ");
            }

            else if (grade >= 2.00)
            {
                Console.WriteLine(" Terrible ");
            }
        }
    }
}



zadacha 2



using System;

namespace zadacha6
{
    class Program
    {
        static void Main(string[] args)
        {
            int num = int.Parse(Console.ReadLine());

            if(num >=1 && num <=3)
            {
                Console.WriteLine(num * 10);
            }
            else if (num >= 4 && num <= 6)
            {
                Console.WriteLine(num * 100);
            }
            else if (num >= 7 && num <= 9)
            {
                Console.WriteLine(num * 1000);
            }
            else
            {
                Console.WriteLine();
            }
        }
    }
}




попринцип има и още задачи но незнам кои точно да ви изпратя тези са едни от последните които си преговарях
