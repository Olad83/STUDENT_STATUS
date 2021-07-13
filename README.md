# STUDENT_STATUS

using System.Timers;
using System.Reflection.Emit;
using System.Data;
using System;

namespace STUDENT_STATUS
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Welcome Student!");
            Console.Write("Are you fulltime or Part-time? :       ");

            string studentStatus = Console.ReadLine();

            if (studentStatus == "Fulltime")

            {Console.Write("what is your course of study? :      ");
            string courseOfStudy = Console.ReadLine();
            Console.WriteLine($"{courseOfStudy} is a good course");
         }
         else
         {
             Console.Write("How many credits are you taking? :      ");
             int amountOfCredit = Convert.ToInt32(Console.ReadLine());
             if (amountOfCredit > 6)
             {Console.WriteLine("That is Too much Units for a part-time student");
            
             }
             else
             {
                 Console.WriteLine("Proceed to Screen");
             }

         }
        }
    }
}
