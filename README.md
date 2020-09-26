# datos-basicos-equipo1.1
programa que te pide tus datos basicos y si tu edad es menor a 18 marque un error 
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
            String CorreoElectronico;
            String DiaMesYAñoDeNacimiento;

            Console.WriteLine("Ingresa Tu nombre");
            Nombre = Console.ReadLine();
            Console.WriteLine();
            
            
            Console.WriteLine("Ingresa Tu nombre");
            ApellidoPaterno = Console.ReadLine();
            Console.WriteLine();
            
            
            
            Console.WriteLine("Ingresa Tu nombre");
            ApellidoMaterno = Console.ReadLine();
            Console.WriteLine();
            
            
            
            Console.WriteLine("Ingresa Tu nombre");
            ocupacion = Console.ReadLine();
            Console.WriteLine();
            
            
            
            Console.WriteLine("Ingresa Tu nombre");
            CorreoElectronico = Console.ReadLine();
            Console.WriteLine();


            Console.WriteLine("Ingresa tu edad: ");
            Edad = Convert.ToInt32(Console.ReadLine());
            if (Edad < 18)
            {
                Console.WriteLine("El usuario es menor de edad, Registro Fallido");
            }
            
        }
    }
}
