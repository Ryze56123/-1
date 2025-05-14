using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _3._9
{
    class Company
    {
        public string name;
        public int persons;
        public int money;                         
        public Company(string name, int persons,
        int money)
        {
            this.name = name;
            this.persons = persons;
            this.money = money;
        }
        public void show()
        {
            Console.WriteLine("В компании " + name +
            " трудятся " + persons + " сотрудников ");
            Console.WriteLine("Фонд зарплаты: " + money);
        }
        public int averageSalary()
        {
            return money / persons;
        }
        class Program
        {
            public static void Main()
            {
                List<Company> comp1 = new List<Company>();
                comp1.Add(new Company("ABCD1", 101, 900001));
                comp1.Add(new Company("ABCD2", 102, 900002));
                comp1.Add(new Company("ABCD3", 103, 900003));
                Console.WriteLine("Исходная коллекция");
                foreach (Company z in comp1)
                    z.show();
                comp1.Remove(comp1[1]); 
                comp1.RemoveAt(0);
                comp1.Insert
                (0, new Company("ABCD4", 104, 900004));
                Console.WriteLine
                ("Преобразованная коллекция");
                foreach (Company z in comp1)
                    z.show();
                Console.ReadKey();
            }
        }
    }
}
