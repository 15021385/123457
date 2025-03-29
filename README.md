# 123457
int a, b, c, d;
            a = int.Parse(Console.ReadLine());
            b = int.Parse(Console.ReadLine());
            c = int.Parse(Console.ReadLine());
            if (a > b)
            {
                d = a; a = b; b = d;
            }
            if (a > c)
            {
                d = a; a = c; c = d;
            }
            if (b > c)
            {
                d = b; b = c; c = d;
            }
            Console.WriteLine(a + "" + b + "" + c);
            Console.ReadLine();
