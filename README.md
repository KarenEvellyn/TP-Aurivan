# TP-Aurivan

string produto;
            double valor, total, a;
            int quantidade;

            Console.WriteLine(" Digite o nome do Produto: ");
            produto = Console.ReadLine();

            Console.WriteLine(" Digite o valor: ");
            valor = double.Parse(Console.ReadLine());

            Console.WriteLine(" Digite a quantidade: ");
            quantidade = int.Parse(Console.ReadLine());
            

            
            total = quantidade * valor;
            a = total/3;

            if (valor < 300)
            {
                Console.WriteLine("Cliente mediano");
                Console.WriteLine("valor da parcela: " + a);
                Console.WriteLine("Valor da compra " + total);
            }
            else (valor > 300)
            {
                Console.WriteLine(" Bom cliente ");
                Console.WriteLine(" Valor de parcela: " + a);
                Console.WriteLine(" Valor da compra " + total);
            }





            Console.ReadLine();
