# ConsoleApp8


        
        using System;
        using System.Collections.Generic;
        using System.Linq;
        using System.Text;
        using System.Threading.Tasks;
        
        namespace ConsoleApp8
        {
            internal class Program
            {
                static void Main(string[] args)
                {
                    //  f(x)= 0.5*(x-3)^2+2 , x=[-2;7] , h=0.1
                    Console.Write($"x\ty");
                    Console.WriteLine();
                    for (double x = -2; x<=7; x += 0.1 ) 
                    {
                        double y = 0.5 * Math.Pow((x-3),2) + 2 ;
                        Console.Write($" {x:f2} ");
                        Console.WriteLine($"\t{y:f2}");
                    }
                    Console.ReadKey();
                }
            }
        }
