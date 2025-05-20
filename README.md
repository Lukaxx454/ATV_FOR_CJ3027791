
int valor;

Console.WriteLine("\n========MENU========");
Console.WriteLine("0 - Para sair         ");
Console.WriteLine("1 - Exercício 1       ");
Console.WriteLine("2 - Exercício 2       ");
Console.WriteLine("3 - Exercício 3       ");
Console.WriteLine("4 - Exercício 4       ");
Console.WriteLine("5 - Exercício 5       ");
Console.WriteLine("6 - Exercício 6       ");
Console.WriteLine("7 - Exercício 7       ");
Console.WriteLine("====================\n");
valor = int.Parse(Console.ReadLine());
switch (valor) {

    case 1:

        int i = 1;
        Console.WriteLine("escreva um número: ");
        int b = int.Parse(Console.ReadLine());

        for (i = 1; i <= b; i++)
        {

            Console.WriteLine(i);
        }
        break;



    case 2:

        int j = 1;
        Console.WriteLine("Escreva um número: ");
        int k = int.Parse(Console.ReadLine());

        for (j = 1; j <= k; j++)
        {
            if (j % 2 == 0)   //para saber se é par
            {
                Console.WriteLine(j);

            }


        }
        break;


    case 3:


        int x = 1001;

        for (; x >= 1000;)
        {
            Console.WriteLine("Entre com um número menor que 1000");
            x = int.Parse(Console.ReadLine());
        }

        int l;
        for (l = 1000; l >= x; l--)
        {
            if (l % 2 == 0)
            {
                Console.WriteLine(l);
            }
        }
        break;

    case 4:

        int soma = 0;
        int p = 0;
        for (; soma < 200;)
        {
            Console.WriteLine("Escreva um número: ");
            Console.WriteLine($"Soma ={soma}");
            p = int.Parse(Console.ReadLine());
            if (p > 0)
                soma = soma + p;

        }
        break;

    case 5:

        int f;
        int num = int.Parse(Console.ReadLine());
        for (f = 1; f <= num; f++)
        {
            if (num % f == 0)
            {
                Console.WriteLine($"Números divisores: {f}");
            }
        }
        break;


    case 6:


        Console.WriteLine("Escreva o 1° número:  ");
        int al = int.Parse(Console.ReadLine());
        int ma = al;
        int me = al;

        for (int w = 1; w < 10; w++)
        {
            Console.WriteLine($"Escreva o {w + 1} número");
            al = int.Parse(Console.ReadLine());

            if (al > ma) ma = al;
            if (al < me) me = al;
        }

        Console.WriteLine($"maior número: {ma}");
        Console.WriteLine($"Menor número : {me}");
        break;

    case 7:

int somap = 0;
        int somai = 0;
        int q = 1;
        for (; q != 0;)
        {
            Console.WriteLine("Escreva um número: ");
            q = int.Parse(Console.ReadLine());
            if (q % 2 == 0)
                somap = somap + q;
            Console.WriteLine($"A soma dos números pares é: {somap}");
            if (q % 2 != 0)
                somai = somai + q;
            Console.WriteLine($"A soma dos números ímpares é: {somai}");
        }
        break;
}
