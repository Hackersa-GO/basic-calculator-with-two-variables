A Calculadora Básica de Duas Variáveis é um programa desenvolvido em Java com o objetivo de reforçar os conceitos fundamentais da linguagem. Ela realiza operações matemáticas simples entre dois números definidos diretamente no código, mostrando os resultados no console. Esse projeto foi criado para quem está começando a aprender Java e deseja praticar o uso de variáveis, operadores aritméticos e a exibição de informações com o comando System.out.println.

O programa utiliza duas variáveis inteiras, representando os valores que serão calculados. Em seguida, são realizadas as operações de soma, subtração, multiplicação e divisão, e cada resultado é impresso de forma clara na tela. O foco está na compreensão da lógica de operações básicas e na estrutura essencial de um programa Java, que começa com a classe pública e o método principal main.

O código é simples e direto. Ele começa declarando duas variáveis, a e b, e depois exibe os resultados das operações entre elas:

public class CalculadoraBasica {
    public static void main(String[] args) {
        int a = 10;
        int b = 5;

        System.out.println("===== CALCULADORA BÁSICA =====");
        System.out.println("Número A: " + a);
        System.out.println("Número B: " + b);
        System.out.println("-------------------------------");
        System.out.println("Soma: " + (a + b));
        System.out.println("Subtração: " + (a - b));
        System.out.println("Multiplicação: " + (a * b));
        System.out.println("Divisão: " + (a / b));
    }
}


Para executar o projeto, é necessário ter o Java JDK instalado e um editor de código como o VS Code, IntelliJ IDEA ou Eclipse. Basta criar um arquivo chamado CalculadoraBasica.java, colar o código acima, compilar com o comando javac CalculadoraBasica.java e depois executar com java CalculadoraBasica. O programa exibirá os resultados diretamente no console, mostrando de forma organizada os valores de entrada e as quatro operações básicas.

O resultado esperado da execução é o seguinte:

===== CALCULADORA BÁSICA =====
Número A: 10
Número B: 5
-------------------------------
Soma: 15
Subtração: 5
Multiplicação: 50
Divisão: 2


Apesar de ser um projeto simples, ele é um excelente exercício para fixar os primeiros conceitos da linguagem Java. A partir desse código, é possível evoluir gradualmente, adicionando novas funcionalidades. Com o avanço dos estudos, o programa pode ser modificado para permitir que o usuário digite os números por meio da classe Scanner, incluir um menu de opções utilizando switch, adicionar verificações de erros como divisão por zero, ou até criar métodos separados para cada operação, deixando o código mais modular e organizado.

Esse projeto foi desenvolvido como parte do aprendizado inicial baseado na playlist de Java do canal DevDojo, e representa um primeiro passo importante para compreender a estrutura, a sintaxe e o raciocínio lógico de programas escritos em Java.
