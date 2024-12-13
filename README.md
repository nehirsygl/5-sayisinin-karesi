# 5-sayisinin-karesi
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp22
{
    internal class Program
    {
        static void Main(string[] args)
        {
            /*
             10 sayısının 3'e bölümünden kalanı bulan C# kodu
            */
            int sayi, kalan;
            sayi = 10;
            kalan = sayi % 3;
            Console.WriteLine(" 10 sayısının 3'e bölümünden kalan: " + kalan);
            Console.ReadLine();
        }
    }
}
