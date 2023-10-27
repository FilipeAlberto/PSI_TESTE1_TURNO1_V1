# Teste de PSI 1 - Turno 1 - Versão 1

## Informação do aluno

    Filipe Alberto

Teste termina às 10:45.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    int i = 5 / 2;
    
    Console.WriteLine($"*\t{i}");

P1 - Resposta

    o que este codigo impressa é um "2".
    Porque onde há um asterisco (*), um espaço em branco (\t) e o valor de i, que eqivalente a 2.

### P2. Considera o seguinte código com um *bug*

    string s = "2.5";
    int i = Convert.ToInt32(s);

    Console.WriteLine(i);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    o codigo têm um bug na parte de converção do numero "2.5".
    não se pode converter um numero decimal com o comando "Convert.ToInt32".

### P3. Escreve um programa que solicite ao utilizador dois números inteiros e apresente a sua soma. Caso o resultado seja um número divisível por 3, deve também ser impressa a mensagem "Múltiplo de 3!"

P3 - Resposta

    using System;

        class Program
        {
        static void Main()
        {
            Console.Write("Digite o primeiro número inteiro: ");
            int numero1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Digite o segundo número inteiro: ");
            int numero2 = Convert.ToInt32(Console.ReadLine());
            
            int soma = numero1 + numero2;

            Console.WriteLine($"A soma dos números é: {soma}");
    
            if (soma % 3 == 0)
            {
                Console.WriteLine("Múltiplo de 3!");
            }
        }
    }


### P4. Tens um repositório git criado localmente, onde estás no ramo 'master'. Queres associá-lo ao repositório remoto contido no url 'https://github.com/PSI/OMeuRepositorioRemoto'. Queres também alterar o nome do ramo atual para 'main'. Deverás enviar os *commits* já feitos localmente para o repositório remoto. Indica os comandos necessários

P4 - Resposta

    os comandos necessarios são: 
    "git branch -m master main";
    "git remote add origin https://github.com/PSI/OMeuRepositorioRemoto"; 
    "git push -u origin main";


