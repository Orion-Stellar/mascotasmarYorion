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
            Console.WriteLine("Anos: " + anosDeVida);
            Console.WriteLine("Animal: " + animal);
            Console.WriteLine("Sonido: " + sonido);
        }

        public void EmitirSonido()
        {
            Console.WriteLine(nombre + " dice " + sonido);
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            Mascota miMascota = new Mascota("Mayo", 4, "gato", "maw");

            miMascota.MostrarInformacion();
            miMascota.EmitirSonido();
        }
    }
}
