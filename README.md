# tarea-1
 class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("desea intrar al bucle?");
            string respuesta = Console.ReadLine();

            while(respuesta != "no")
            {

                Console.WriteLine("Estas en el bucle");

                Console.WriteLine("Dijite su nomnbre");

                string nombre = Console.ReadLine();

                Console.WriteLine($"senor {nombre} si usted desea salir diga que no");

                respuesta = Console.ReadLine();


           
            }

            Console.WriteLine("estas fuera");
        }

    }
}
