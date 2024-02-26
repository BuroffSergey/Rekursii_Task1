# Rekursii_Task1

using System;

class Program
{
    static void PrintNaturalNumbers(int M, int N)
    {
        if (M <= N)
        {
            Console.Write(M + ","); 
            PrintNaturalNumbers(M + 1, N); 
        }
    }

    static void Main()
    {
        Console.Write("Введите значение M:  ");
        int M = int.Parse(Console.ReadLine());

        Console.Write("Введите значение N: ");
        int N = int.Parse(Console.ReadLine());

        
        PrintNaturalNumbers(M, N);
    }
}
