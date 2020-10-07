using System;

namespace ConsoleApp20
{
    class Program
    {
        static void Main(string[] args)
        {
            String Nombre;
            String ApellidoPaterno;
            String ApellidoMaterno;
            int Edad;
            String Ocupacion;
            String Correo;
String Mes;

            Console.WriteLine("Ingresa Tu nombre");
            Nombre = Console.ReadLine();
            Console.WriteLine(Nombre);

            Console.WriteLine("Ingresa Tu Apellido Paterno");
            Apellido Paterno=Console.ReadLine();
            Console.WriteLine(Apellido Paterno);
            
            Console.WriteLine("Ingresa Tu Apellido Materno");
            Apellido Materno=Console.ReadLine();
            Console.WriteLine(Apellido Materno);

            Console.WriteLine("Ingresa tu edad: ");
            Edad = Convert.ToInt32(Console.ReadLine());
            if (Edad <= 18)
            {
                Console.WriteLine("El usuario es menor de edad, Registro Fallido");
            }
        }
    }
}
