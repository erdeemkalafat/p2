using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using static _05._11._2021.Metodlarım;

namespace _05._11._2021
{
    class Program
    {
        static void Main(string[] args)
        {
            List<int> bölenSayılar = new List<int> { 8, 2, 7, 5 };
            List<int> sıralıBölenSayılar = bölenSayılar.OrderByDescending(a=>a).ToList();
             
            foreach (var böleninBiri in sıralıBölenSayılar)
            {
                Console.WriteLine(böleninBiri);
            }
            Console.ReadLine();
        }
    }
}
