# Tarefas de Java
Um repositório onde está algumas tarefas que fiz da matéria Linguagem de Programação Orientada a Objetos 1, feita em Java, no curso de Análise e Desenvolviment de Sistemas na UFPR.


## Tarefa 01
01) Crie um programa “Nome” que leia um nome completo na linha de comando e imprima-o ao contrário. Por exemplo, a linha de comando java Nome Rafael Wandresen deve imprimir:
<br>Wandresen
<br>Rafael

02) Implemente um programa que receba da linha de comando 3 argumentos. O primeiro e o segundo argumento são números reais e o terceiro argumento é a operação. Teste o seu programa com os seguintes casos de testes:
<br>java Calculadora 3 4 +
<br>7.0
<br>java Calculadora 3 4 –
<br>-1.0
<br>java Calculadora 3 4 /
<br>0.75
<br>java Calculadora 3 4 X
<br>12.0

## Tarefa 02
01) Faça uma classe executável que dados a distância percorrida (em Km) e o tempo gasto em uma viagem (em horas), informe a velocidade média do carro, sabendo que Velocidade = S/T (variação de distância / variação do tempo). Imprima o valor com duas casas decimais.

02) Faça uma classe executável que dados a quantidade de DVDs que uma vídeo locadora possui e o valor que ela cobra por cada aluguel, informe:
    - a. Sabendo que um terço dos DVDs são alugadas por mês, o seu faturamento anual.
    - b. Sabendo que quando o cliente atrasa a entrega, é cobrada uma multa de 10% sobre o valor do aluguel e que um décimo das fitas alugadas no mês são devolvidas com atraso, o valor ganho com multas por mês.
    - c. Formate a saída para aparecer com duas casas decimais e (R$) na frente.
    - d. Faça comentários na classe e gere o JavaDoc.

03) Construa um programa que leia do teclado dois pontos em um plano (x,y) e informe a distância entre eles.

04) Construa um programa que leia os coeficientes de uma equação do segundo grau do teclado e mostre os valores de x da equação.
    - a. Verifique na documentação Java as operações matemáticas da classe Math;
    - b. Não é necessário validar tipos de raízes;
    - c. Dados para teste:
        - x² – 9 = 0 Resultado: x = 3 e x = -3
        - x² -9x = 0 Resultado: x = 0 e x = 9
        - 3x² -7x + 2 = 0 Resultado: x = 1/3 e x = 2
        - -x² + 4x – 4 =0 Resultado: x = 2 e x = 2

05) Implemente um programa que calcule o bônus anual de um funcionário de uma empresa. O programa pede para o usuário os seguintes dados: Cargo do funcionário e salário atual. Se o cargo for diretor o sistema pede quantidade de departamentos gerenciados. Se o cargo for gerente o sistema pede a quantidade de pessoas gerenciadas. Não é necessário fazer tratamento de entrada de dados.
<br>O cálculo do bônus anual segue as seguintes regras:
    - a. Para Diretor: 4 salários + R$3000,00 por departamento gerenciado
    - b. Para Gerente: 2 salários + R$100,00 por pessoa gerenciada
    - c. Para Analista: 1 salário
    - d. Para Programador: 0,8 salário
    - e. Para Auxiliar de Limpeza: 0,5 salário

06) Escreva um programa que tenha como entrada do usuário, através do teclado, um número inteiro positivo. Imprima a série de Fibonacci (0, 1 , 1, 2, 3, 5, 8, 13, 21, ...) até que o número da série seja maior que o número fornecido pelo usuário.

## Tarefa 03
01) Construa um programa que seja capaz de efetuar a média de todos os argumentos inteiros ou reais recebidos do teclado e imprimi-los. Argumentos inválidos devem ser desconsiderados (Imprimir uma mensagem para cada valor inválido.), sem provocar a exibição de exceções (Exiba uma mensagem para o usuário pedindo a ele que informe novamente o valor). O usuário deve digitar S quando desejar encerrar a entrada de dados;

02) Faça uma classe executável que dado um conjunto de 20 elementos numéricos, informe a soma de todos os números pares. Faça a validação de dados inválidos informando o usuário, e fazendo-o repetir a digitação.

03) Escreva um programa que leia do teclado 7 valores reais correspondentes ao índice pluviométrico diário de uma semana. Após a leitura, o programa deve determinar o índice pluviométrico médio, máximo e mínimo com o respectivo dia da ocorrência;

04) Escreva um programa com os seguintes passos: 
    - a. Peça ao usuário que informe quantos funcionários existem na empresa. 
    - b. Instancie um array de strings e um array de doubles com o tamanho informado. 
    - c. Peça ao usuário que informe o nome e o salário de cada funcionário e armazene o nome no array de strings e o salário no array de doubles. 
    - d. Calcule a média salarial da empresa. 
    - e. Imprima a lista de nomes/salários que estão acima da média salarial. 
<br>Obs.: Faça o tratamento das entradas de dados. Se o usuário informar um salário inválido, peça para ele informar novamente. Imprima os salários com duas casas decimais. Os nomes devem conter ao menos 3 caracteres.

05)  Faça um programa que leia uma frase e informe se ela é um palíndromo ou não. Uma frase é um palíndromo quando pode ser lida tanto da forma usual, quanto de trás para frente. O programa deve ignorar maiúsculas e minúsculas na avaliação. Insira as frases sem acentuação;
<br>Dica: será necessário verificar os métodos disponíveis na classe String;
    - "Socorram-me, subi no ônibus em Marrocos”
    - "A Rita, sobre vovô, verbos atira."
    - "Olé! Maracujá, caju, caramelo."

06) Construa um programa que calcule o determinante de uma matriz 3 x 3 fornecida pelo usuário;

07) Escreva um programa que calcule a soma das diagonais principal e secundária. O programa deve perguntar ao usuário a dimensão da matriz. Baseado na dimensão da matriz o programa deve pedir ao usuário para preencher os valores da matriz (faça um método estático que receba a referência de uma matriz e a preencha). Com a matriz preenchida faça outro método estático que calcule a soma das diagonais. Imprima o resultado.

08) Faça um programa que calcule o desvio padrão de um determinado número de amostras. O número de amostras deve ser pedido ao usuário no início do programa. Utilize array para armazenar as amostras. Os valores das amostras devem ser digitadas pelo usuário, uma a uma, como números decimais. 
<br>`𝑠 = √∑(𝑋𝑖 − 𝑋̅)²/𝑛 − 1`

## Tarefa 04
01) Escreva a estrutura de uma classe (atributos e métodos) para representar uma Pessoa (nome, idade e endereço):
    - a. Compile a classe;
    - b. Crie uma outra classe que utilize um objeto Pessoa. Leia informações de nome, idade e endereço, e mostre todos os dados e a idade da pessoa. O programa deve usar os métodos do objeto.
    - c. Acrescente dois métodos:
        - fazAniversario(): que incrementa a idade da pessoa
        - imprime(): Que imprime de forma legível todos os atributos da pessoa
    - d. Altere o método main (que utiliza a classe pessoa) para que instancie uma pessoa, utilize algumas vezes o método fazAniversario e imprima os atributos do objeto pessoa.

02) Crie uma classe para representar um Ponto3D, com atributos e métodos (x, y, z, cor, intensidade). Crie os métodos gets e sets. Crie os seguintes métodos:
    - a. public double caluclaDistancia(Ponto3D p) -> recebe como parâmetro um ponto 3D, e retorna a distância entre o objeto específico e o ponto.
    - b. public static void main(String args[]) -> Criar uma nova classe chamada UsaPonto3D e um método principal que faz testes utlizando a função calculaDistancia.

03) Crie uma classe Circunferencia, que armazene o valor do raio e seja capaz de informar sua área. Crie uma classe UsaCircunferencia para testar objetos da classe Circunferencia.

## Tarefa 05
01) Escreva a estrutura de uma classe (atributos e métodos) para representar um aluno (nome, matricula, curso, período, disciplinasMatriculadas(array de String) e endereço):
    - a. Compile a classe.

    - b. Crie um construtor para essa classe com a seguinte assinatura: 
        <br>`public Aluno(String nome, String matricula, String curso, int periodo, int idade, int quantidadeDisciplinasPermitidadas)`
    <br>Onde a quantidadeDisciplinasPermitidadas representa a quantidade de disciplinas que o aluno pode se matricular. Deve ser utilizada para redimensionar o array de Strings.

    - c. Acrescente três métodos:
        - String fazMatricula(String disciplina): inclui uma disciplina no array de Strings. Se o aluno já ultrapassou a quantidade de disciplinas que pode se matricular, então o sistema retorna para este método uma string informando: “Quantidade de disciplinas excedida. O limite de disciplinas para este aluno é de 2 disciplina(s). Se desejar, cancele a matrícula de uma das disciplinas e faça a nova matrícula.” Se o aluno não puder ser matriculado em nenhuma disciplina (tamanho do array=0), então o método deve retornar: “Este aluno não pode ser matriculado em nenhuma disciplina, por favor, fale com a secretaria.” Se foi matriculado com sucesso a seguinte String é retornada: “Matrícula na disciplina “LPOO” executada.”

        - String cancelarMatricula(String disciplina): exclui a disciplina do array de Strings. Se o aluno não estiver matriculado na disciplina, o método deve retornar: “Aluno não está matriculado na disciplina LPOO, portanto não é possível cancelar esta matrícula.”. Se o aluno realmente estiver matriculado na disciplina, então o método deve retornar “Cancelamento da matrícula da disciplina LPOO executado com sucesso.”

        - String imprime(): Método que retorna uma String de forma legível com todos os atributos de aluno e as disciplinas matriculadas no seguinte formato:
        ```
        -----------------------------------------------------------------
        Nome do Aluno: Rafael Romualdo Wandresen
        Matricula: GRR20130101
        Curso: TADS
        Periodo: 4
        Disciplinas Matriculadas: Gestão de Projetos; LPOO
        -----------------------------------------------------------------
        ```

    - d. Crie uma outra classe (SistemaAcademico) que utilize objetos do tipo Aluno. Nessa classe instancie um array de Alunos que armazene os alunos criados. Crie um menu com as seguintes opções: 
        - 1 – Cadastrar Aluno
        - 2 – Excluir aluno por nome
        - 3 – Listar Alunos
        - 4 – Matricular Aluno em Disciplina
        - 5 – Cancelar Matrícula
        - 6 – Imprimir lista Alunos e  Disciplinas Matriculadas

    - Cada um destes itens do menu deve ter um método associado com os seguintes métodos. Criar todos os métodos estáticos:
        - 1. public static void cadastrarAluno(Aluno aluno)
        - 2. public static void excluirAlunoPorNome(String nomeAluno)
        - 3. public static Aluno[] listarAlunos()
        - 4. public static String matricularAlunoEmDisciplina(Aluno aluno, String disciplina). Onde o retorno informa o que ocorreu com a matricula do aluno, conforme especificado no método fazMatricula.
        - 5. public static String cancelarMatricula(Aluno aluno, String disciplina)
        - 6. public static String imprimirListaDeAlunoseDisciplinas()

    - e. Quando o sistema iniciar deve pedir ao usuário para informar a quantidade de alunos que serão cadastrados. Com essa informação dimensione o array.
    - f. Quando o usuário optar pela opção 4, se for a primeira disciplina do aluno, o sistema deve perguntar em quantas disciplinas o aluno deve ser matriculado. Com essa informação dimensione o array de Strings.

02) Altere o código da classe Ponto 3D para que os métodos tenham o modificador public, protected e private.
    - a. Para cada uma das alterações tente compilar e rodar.
    - b. Em algum dos casos ocorreu erro de compilação ou execução? Quais e porque?

03) Modifique a classe Bicicleta para encapsular seus atributos como privados, crie os métodos de acesso a estes atributos e crie dois construtores para ela:
    - a. Um construtor que recebe como parâmetro o número máximo de marchas da bicicleta (crie um atributo privado para armazenar este valor)
    - b. Um construtor padrão (sem argumentos) que inicie o número máximo de marchas como 18.
    - c. Ambos os construtores devem criar uma bicicleta parada.
    - d. Os métodos que mudam a marcha devem avaliar se o número máximo de marchas foi alcançado e não permitir a mudança nestes casos.

04) Implemente uma classe contendo apenas métodos estáticos capazes de realizar todas as conversões de temperatura possíveis entre as unidades Celsius, Farenheit e Kelvin. São conhecidas as seguintes relações de conversão: `F = 9*C/5 + 32` e `K = C + 273`. Demonstre a utilização do objeto. Utilize, neste programa, uma estrutura de controle switch para identificar a conversão solicitada pelo usuário;

## Tarefa 06
01) Crie e implemente uma hierarquia de classes para a classe Funcionario. Imagine que Funcionario represente uma classe em um sistema de uma Empresa. Crie classes para herdar de funcionário (Gerente, Diretor e Analista). O gerente deve conter um array de Funcionarios e o Diretor deve conter um array de Departamentos. Implemente um método abstrado na classe Funcionario chamado getBonus. O cálculo do bônus anual segue as seguintes regras. Implemente estas regras utilizando conceitos de polimorfismo:
    - a. Para Diretor: 4 salários + R$3000,00 por departamento gerenciado
    - b. Para Gerente: 2 salários + R$100,00 por pessoa gerenciada
    - c. Analista: 1 salário
    - d. Programador: 0,8 salário
    - e. Auxiliar de Limpeza: 0,5 salário
<br>Crie uma classe chamada SistemaRH que instancie os objetos e imprima um relatório com os funcionários da empresa. A classe SistemaRH deve ter um método estático para imprimir o relatório: public static void imprimeRelatorio(Funcionario[] listaFuncionarios).

02) Modifique o sistema acadêmico criado no item 3 da lista 4 para utilizar orientação a objetos com herança. Crie uma classe pessoa, coloque os atributos da classe aluno que dizem respeito a pessoa nessa classe e faça uma relação de herança entre as classes aluno e professor. Crie a classe professor (deve herdar de pessoa). No sistema acadêmico permita criar professores e relacionar as disciplinas ministradas. Crie uma classe que represente as disciplinas e faça o relacionamento com as classes Aluno e Professor.

03) Implemente a estrutura de classes representada na figura a seguir, de acordo com as instruções abaixo:
    ![image](https://user-images.githubusercontent.com/58374776/146078393-f8825704-993f-410e-b674-f82943d1b38d.png)
    <br>
    - a. A implementação de operacao1() deve mostrar no console que passou por tal método e o valor dos atributos do objeto;
    - b. A implementação de operacao2() deve mostrar no console que passou por tal método;
    - c. O construtor C() deve inicializar seus atributos 1 e 2 com “VAZIO”e -999.99f, respectivamente;
    - d. O construtor C(String p1, float p2) deve inicializar seus atributos com os valores providos por parâmetro;
    - e. Os construtores de C_12 devem chamar os construtores respectivos da superclasse e inicializar a matriz atributo3. Se o construtor for sem parâmetros, a matriz deve ser 2 x 2 e seus elementos possuir valor 0. Se o construtor possuir parâmetros, a matriz deve ser 3 x 3 e seus elementos devem possuir valor 1;
    - f. O método main deve possuir o código indicado a seguir. Entenda a origem de todas as saídas;

``` 
    public static void main (String args[]){
        System.out.println ("Iniciando o programa...");
        
        System.out.println ("Instanciando C1_2 sem parametros:");
        C1_2 objC1 = new C1_2();
        
        System.out.println ("Instanciando C1_2 com parametros:");
        C1_2 objC2 = new C1_2("XPTO", 3.141516f);
        
        System.out.println ("Chamando operacoes na instancia 1:");
        objC1.operacao1();
        objC1.operacao2();
        
        System.out.println ("Chamando operacoes na instancia 2:");
        objC2.operacao1();
        objC2.operacao2();
        
        System.out.println ("Instanciando objeto em referencia para interface:");
        I1 objC3 = new C1_2("YSBC", 1.99f);;
        
        System.out.println ("Chamando operacoes na referencia para interface:");
        objC3.operacao1();
    }
```

04) Altere as classes Quadrado e Circunferencia dos exercícios de aulas anteriores para que implementem a interface Superficie indicada abaixo. Para testar, atribua instâncias de Quadrado e Circunferencia para uma referência à interface e invoque métodos a partir dela.
```
public interface Superficie {
    public double area();
}
```

05) Crie uma estrutura de classes que represente diferentes tipos de Veículos. A superclasse chama-se Veiculo. Esta possui três subclasses, VeiculoTerrestre, VeiculoAereo, VeiculoAquatico, que possuem, respectivamente, as subclasses Carro e Trem, Avião e Barco. Crie atributos, getters e setters coerentes com a hierarquia. Toda a hierarquia deve possuir uma operação andar(), que deve ser abstrata nos dois primeiros níveis e implementada nas classes de nível mais baixo. Sua implementação consiste em imprimir no console o movimento executado.
    - a. A classe Veiculo deve possuir um construtor com parâmetros que inicializa seus atributos. As classes filhas devem possuir, também, construtores com parâmetros que, além de chamar o construtor da superclasse, define seus próprios atributos.
    - b. Para testar o funcionamento das classes, faça um programa que permita ao usuário escolher qual tipo de veículo deseja criar e realize o movimento correspondente. Independentemente do tipo de veículo escolhido, a instância deve ser do tipo Veiculo;
    - c. Utilizando a hierarquia de classes, faça um programa em que o usuário informa dados de veículos. O programa inicia solicitando ao usuário quantos veículos deseja informar. Para cada um dos veículos, o programa deve identificar seu tipo e ler as informações correspondentes. Os dados informados devem ser armazenados em um único vetor, que deve conter todos os objetos de veículos.
    - d. Depois de ler todas as informações, o programa deve invocar o método andar() de todos os veículos armazenados.

06) Crie uma classe que contenha um método capaz de efetuar a soma das áreas de elementos de um único vetor contendo objetos do tipo Retangulo, Triangulo e Circunferencia. Construa um programa para testar este método.

## Tarefa 07
01) Considere a classe Bicicleta abaixo:
```
class Bicicleta {
    int cadencia = 0;
    int velocidade = 0;
    int marcha = 1;
    
    void mudarCadencia(int novoValor){
        cadencia = novoValor;
    }
    
    void mudarMarcha(int novoValor){
        marcha = novoValor;
    }
    
    void aumentarVelocidade(int incremento){
        velocidade = velocidade + incremento;
    }
    
    void aplicarFreios(int decremento){
        velocidade = velocidade - decremento;
    }
    
    void printStates(){
        System.out.println("cadencia = " + cadencia + " velocidade = " + velocidade + " marcha = " + marcha);
    }
}
```
- Crie um tratamento de exceção (com exceções monitoradas) para os seguintes casos:
    - valores de velocidade negativo ou superior a 100 km/h
    - valores de RPM negativo,
    - valores de Marcha negativo ou superior a 24.
    - a. Lance estas exceções nos métodos setVelocidade, setRPM e setMarcha
    - b. Crie um construtor para a classe Bicicleta
    - c. Crie uma classe UsaBicicleta que teste estes casos. Faça o tratamento qualificado
    - das exceções nesta classe.

02) Modifique a classe Retangulo, para que uma exceção IllegalArgumentException seja lançada se os lados informados forem negativos. Adapte adequadamente o programa principal, para que a exceção seja capturada.

03) Crie uma classe com um método main, que receba do usuário valores de entrada (utilize a classe Scanner) e retorne a soma e a média destes valores. Por meio de tratamento de exceção, o programa deve pedir ao usuário que repita a digitação, quando o valor digitado não for um numérico válido. O usuário também tem a opção de sair do programa digitando a letra “S” ou “s” no lugar de um número. Abaixo está um exemplo de saída para este programa:
```
Informe os números na sequencia solicitada.
Para sair digite 'S'
Numero 1=5
Numero 2=5
Numero 3=tr5
Erro de entrada.
tr5 não é um numérico válido. Tente novamente ou digite S para sair.
Numero 3=s
A soma dos número digitados é=10.0
A média dos números digitados é=5.0
```

04) Retome o exercício 3 da Semana 05. Crie uma exceção especializada e monitorada para as classes Gerente e Diretor. No caso da classe Gerente essa exceção deve ser lançada no construtor e no método set caso o array de funcionários tenha um tamanho menor do que 5. No caso do Diretor o array de departamentos não pode ser menor do que 2. Ou seja, a regra de negócios diz que um Gerente não pode ter uma equipe menor do que 5 pessoas e um diretor deve dirigir no mínimo 2 departamentos. Faça uma classe que teste essas opções e informe ao usuário essas condições.

## Tarefa 08
01) Seguindo os passos vistos nos slides criar uma aplicação onde o usuário coloque o Nome em um campo da tela e o sobrenome em outro. No rodapé da tela deve aparecer o Nome e o sobrenome concatenado. Não devem existir botões. Conforme o usuário digita as informações, estas aparecem no rodapé da janela. Capture os eventos do teclado para isso.
    - Dica: Olhar na documentação do Java as classes `KeyAdapter` e `KeyEvent`.

02) Construa uma aplicação Swing que converta uma medida de volume expressa em litros para sua equivalente expressa em galões, sabendo que `1 galão = 3.785 litros`. O valor de entrada, em litros, deve ser fornecido em uma caixa de texto JTextField, a conversão acionada por um botão JButton e o resultado exibido em um rótulo JLabel.

03) Crie uma interface gráfica em Swing para o sistema acadêmico criado em lista anterior.
