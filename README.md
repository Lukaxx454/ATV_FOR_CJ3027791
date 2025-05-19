// Questão 1

//int i = 1;
//Console.WriteLine("escreva um número: ");
//int b = int.Parse(Console.ReadLine());

//for (i = 1; i <= b; i++)
//{

//    Console.WriteLine(i);
//}



//Questão-2

//int i = 1;
//Console.WriteLine("Escreva um número: ");
//int b = int.Parse(Console.ReadLine());

//for (i = 1; i <= b; i++)
//{
//    if (i % 2 == 0)   //para saber se é par
//    {
//        Console.WriteLine(i);

//    }


//}


//Questão-3


//int x = 1001;

//for (; x >= 1000;)
//{
//    Console.WriteLine("Entre com um número menor que 1000");
//    x = int.Parse(Console.ReadLine());
//}

//int i;
//for (i = 1000; i >= x; i--)
//{
//    if (i % 2 == 0)
//    {
//        Console.WriteLine(i);
//    }
//}


//Questão-4

//int soma = 0;
//int p = 0;
//for (; soma < 200;)
//{
//    Console.WriteLine("Escreva um número: ");
//    Console.WriteLine($"Soma ={soma}");
//    p = int.Parse(Console.ReadLine());
//    if (p > 0)
//        soma = soma + p;

//}

//Questão-5

//int i;
//int num = int.Parse(Console.ReadLine());
//for (i = 1; i <= num; i++)
//{
//    if (num % i == 0)
//    {
//        Console.WriteLine($"Números divisores: {i}");
//    }
//}


//Questão-6


//Console.WriteLine("Escreva o 1° número:  ");
//int al = int.Parse(Console.ReadLine());
//int ma = al;
//int me = al;

//for (int i = 1; i <10; i++)
//{
//    Console.WriteLine($"Escreva o {i + 1} número");
//    al = int.Parse(Console.ReadLine());

//    if (al > ma) ma = al;
//    if (al < me) me = al;
//}

//Console.WriteLine($"maior número: {ma}");
//Console.WriteLine($"Menor número : {me}");


//Questão-7

//int somap = 0;
//int somai = 0;
//int p = 1;
//for (; p != 0;)
//{
//    Console.WriteLine("Escreva um número: ");
//    p = int.Parse(Console.ReadLine());
//    if (p % 2 == 0)
//        somap = somap + p;
//    Console.WriteLine($"A soma dos números pares é: {somap}");
//    if (p % 2 != 0)
//        somai = somai + p;
//    Console.WriteLine($"A soma dos números ímpares é: {somai}");
//}
