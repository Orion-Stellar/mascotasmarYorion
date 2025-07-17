using System;

namespace Mascota
{
    class Mascota
    {
        private string nombre;
        private int anosDeVida;
        private string animal;
        private string sonido;

        public Mascota(string nom, int anos, string anim, string son)
        {
            nombre = nom;
            anosDeVida = anos;
            animal = anim;
            sonido = son;
        }

        public void MostrarInformacion()
        {
            Console.WriteLine("Nombre: " + nombre);
            Console.WriteLine("Años: " + anosDeVida);
            Console.WriteLine("Animal: " + animal);
            Console.WriteLine("Sonido: " + sonido);
        }

        public void EmitirSonido()
        {
            Console.WriteLine(nombre + " dice " + sonido);
        }

        public int GetEdad()
        {
            return anosDeVida;
        }

        public void SetEdad(int nuevaEdad)
        {
            anosDeVida = nuevaEdad;
        }

        public int CalcularEdadHumana()
        {
            return anosDeVida * 7;
        }

        public void DescribirMascota(string color)
        {
            Console.WriteLine(nombre + " es una mascota de color " + color + ".");
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            Mascota mascota1 = new Mascota("Mayo", 4, "gato", "maw");
            mascota1.MostrarInformacion();
            mascota1.EmitirSonido();
            Console.WriteLine("Edad humana: " + mascota1.CalcularEdadHumana());
            mascota1.DescribirMascota("gris");

            Mascota mascota2 = new Mascota("Kira", 2, "perro", "arf");
            mascota2.MostrarInformacion();
            mascota2.EmitirSonido();
            Console.WriteLine("Edad humana: " + mascota2.CalcularEdadHumana());
            mascota2.DescribirMascota("café");

            mascota2.SetEdad(5);
            Console.WriteLine("Nueva edad de Kira: " + mascota2.GetEdad());
            Console.WriteLine("Nueva edad humana de Kira: " + mascota2.CalcularEdadHumana());
        }
    }
}
