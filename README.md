# Retorna-Numeros-Primos-CSharp
Numeros Primos

int valor = 0, cont = 0;
            Console.WriteLine("Informe um valor");

            valor = int.Parse(Console.ReadLine());

            for (int i = 1; i < valor; i++)
            {
                cont = 1;
                for (int j = 1; j < i; j++)
                {
                    if (i % j == 0)
                    {
                        cont++;
                    }
                }
                if (cont == 2)
                {
                    Console.WriteLine("Numeros primos = " + i);
                }
            }
