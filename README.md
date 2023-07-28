class Program
{
    static void Main(string[] args)
    {
            Console.WriteLine("type your age");
            int age = int.Parse(Console.ReadLine()); 
        
        
            if(age >=0 && age<=11)
        {
            Console.WriteLine("you is a kid");
        }

            else if(age>=12 && age<= 18)
            {
                Console.WriteLine("you is a teenager");
            }
            else if(age >= 19 && age <=60)
            {
                Console.WriteLine("you is a adult");
            }
            else
            {
                Console.WriteLine("you is elderly");
            }


    }
}
