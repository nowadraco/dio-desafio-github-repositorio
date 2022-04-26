# Lógica de Programação

Programar e resolver problemas então sempre e necessário montar a solução em um mapa mental, sempre fazendo uma sequencia de atos ate chegar na solução do problema.

Logica de programação significa apenas contextualizar a logica na programação de computadores, buscando a melhor sequencia de ações para solucionar um problema.

## Metacognição
E pensar como a você pensa.
exemplo: você vai em uma loja comprar duas camiseta sabendo que cada uma custa R$ 50,00 e se você levar as duas camisetas você ganha 20% de desconto na compra, com essas informações você usa o pensamento logico  para montar seu mapa mental para saber quanto será sua compra.

> camiseta 1 R$ 50,00
camiseta 2 R$ 50,00
total R$ 100,00
desconto 20%
desconto em R$ 20,00
preço a pagar R$ 80,00

Também você pode usar a abstração para simplificar a solução 
 
sabendo que o valor de duas camisetas terá o custo de R$100 e o desconto e 20% você já sabe que irar pagar 80% do valor do produto que seria R$  80,00 a ser pago.

> total da compra R$ 100,00
porcentagem a pagar 80%
valor da compra com desconto R$80,00

## Abstração
e a Habilidade de concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais.

Exercício final
criar um mapa metal para resolver um determinado problema, por exemplo calcular a média aritmética de 4 notas, sabendo que as notas são as seguintes:

> nota 1: 5
nota 2: 7
nota 3: 10
nota 4: 3

> somar as 4 notas:
5+7=12
10+3=13
12+13=25
25/4= 6,25

> abstração
juntar números impares e pares para soma na medida do possível
7+3+5=15
15+10=25
25/4 = 6,25

media aritmética e de 6,25.

## Algoritmos e pseudocódigo

### Algoritmo
É uma sequencia de passos que resolve um problema. exemplo algoritmo:

> Inicio-dia 
Acordei 
Levantei da cama
Troquei de roupa
Escovei os dentes 
Fui a padaria 
Tomei cafe
Escovei os dentes 
Fui ao trabalho 
...
Fim-dia

Conhecer o site:
https://studio.code.org/s/mc/lessons/1/levels/1

### Pseudocódigo
É uma forma genérica de escrever um algoritmo, utilizando uma linguagem simples (nativa a quem o escreve, de forma a ser entendida por qualquer pessoa) sem necessidade de conhecer a sintaxe de nenhuma linguagem de programação.
 
## exercício final 

> 1 - criar um algoritmo do seu dia 
>2 - resolver todos os quebra cabeças do site https://studio.code.org/s/mc/lessons/1/levels/1
3 - Família de pinguins escrever o pseudocódigo para resolver o problema

site:  https://rachacuca.com.br/jogos/pinguins-numa-fria/

#### soluções
**1-**
> Início dia
acordei
levantei
troquei de roupa
escova os dentes
fiz café
tomei café
escovei os dentes
lavei a louça
tomei um banho 
me troquei
arrumei para ir ao trabalho 
sai de casa 
fui para o ponto do ônibus
cheguei no ponto de ônibus
esperei o ônibus
subi no ônibus
andei de ônibus até o ponto próximo ao trabalho 
desci no ponto próximo ao trabalho
andei ate o trabalho
trabalhei
andei ate o ponto de ônibus
cheguei no ponto de ônibus 
esperei o ônibus
subi no ônibus
andei no ônibus ate o ponto próximo a minha casa
desci no ponto próximo a minha casa 
andei ate minha casa 
entrei dentro de casa 
tomei banho 
me troquei 
fui fazer a janta 
jantei 
lavei a louça 
assistir TV
deitei na cama 
dormi
fim-dia

**2-**
( Fazer no site )

**3-**
> colocar filho  pinguim laço vermelho no gelo coloca pai pinguim laço vermelho no gelo 
atravessa
desce o pai pinguim laço vermelho 
atravessa
sobe filho pinguim laço verde
atravessa 
desce filho pinguim laço vermelho 
atravessa 
sobe pai pinguim laço verde 
atravessa 
desce pai pinguim laço verde
atravessa
sobe filho pinguim laço azul
atravessa 
desce filho pinguim laço verde
atravessa
sobe pai pinguim laço azul
atravessa 
desce pai pinguim laço azul 
desce filho pinguim laço azul

## Aprendendo fluxograma, variáveis e constantes

### Fluxograma
Um fluxograma é um diagrama que descreve um processo, sistema ou algoritmo podemos entendê-lo, na pratica como a documentação dos passos necessário para execução de um processo qualquer

### Variáveis 
Na programação uma variável e um objeto ( uma posição frequentemente localizada na memoria capaz de reter e representar um valor ou expressão, outra definição de uma variável é um espaço na memória do computador destinado a um dado que e alterado durante a execução do algoritmo
dentro de um pseudocódigo declarar sempre as variáveis sempre depois de  iniciar o programa 

Tipos de variáveis
numéricas, caracteres, alfanuméricas ou logicas.

### Constante
As constantes são valores imutáveis e não são alterados durante a vida útil do programa

### Tomadas de decisões e expressões
 
1. conhecer as expressões aritméticas, literais e as expressões relacionais 
2. entender e aplica as tomadas de decisão em um algoritmo 

> Expressões aritméticas
são expressões que utilizam operadores aritméticos e funções aritméticas envolvendo constate e variáveis

> exemplo:
50+50
total+50

### operadores aritimeticos
> soma +
subtração -
multiplicação *
divisão /
potenciação ^
porcentagem %

### Expressões literais 
são expressões com constantes e/ou variáveis que tem como resultado valores literais. iremos =utilizar expressões literais na atribuição de calor para uma variável ou constante.

#### exemplo:
> nome= "José da Silva"  atribuindo valor a variável ou/e constante 
nome < "José da Silva" pseudocódigo atribuindo valor a variável ou/e constante 
média= (nota1+nota2+nota3+nota4)/4  atribuindo o resultado da expressão para a variável

variável | comando de atribuição /operação | procedimento
---|---|---
A | A = 2 | armazena o valor 2 na variável A
B | B = A+3 | soma o valor de A (2) com 3 e armazena em B(5)
C | C = A+b | soma o valor de A (2) e o valor B (5) e armazena em C (7)

### Operadores relacionais
operador | siginificado | o que faz
---|---|---
.>| maior que x>y| x é maior que y?
.>= | maior ou igual x>=y | x é maior ou igual a y?
.< | menor que x<y x | é menor que y?
.<= | menor ou igual x<=y | x é menor ou igual a y?
.== | igualdade x==y | x é igual y?
.!= | diferente de  x!=y também dessa forma x<>y| x é diferente de  y?

obs: desconsiderar os . na frente do operador relacionais 

### Tomada de decisão
quando escrevemos programas, geralmente ocorre a necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução


### Concatenação
e um termo usado em computação para designar a operação de unir conteúdos de duas strings ( e uma sequencia de caracteres )

agrupamento de duas ou mais células que incluindo formulas textos outras informações contida no seu interior da origem a um único resultado

### Estrutura de repetição
dentro da logica da programação e uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com a condição ou com um contador

## Linguagens de programação e o Portugol

Linguagem de programação e uma linguagem escrita e formal que especifica em conjunto de instruções e regras usadas para gerar programas ( software). um software pode ser desenvolvido para rodas em um computador, dispositivo móvel ou em qualquer equipamento que permitia sua execução.
o que é óbvio para você, certamente não e obvio para uma máquina. e se você quer a máquina faça algo pra você, você precisa , "falar com ela"
A função das linguagens de programação é servir de um meio de comunicação entre computadores e humanos 

### linguagens de alto nível e baixo nível
>alto nível
essas são aquelas cuja sintaxe de aproxima mais da nossa linguagem e se distanciam mais da linguagem de máquina 

>baixo nível
é aquela que se aproxima mais da linguagem de máquina, essas são as que você precisa ter o conhecimento direto da arquitetura do computador para fazer alguma coisa.

### Compiladas ou interpretadas

>compiladas 
e uma linguagem de programação em que o código fonte, e executado diretamente pelo sistema operacional ou pelo processador, após se traduzido por meio de um processo chamado compilação

>interpretadas
é uma linguagem de programação em que o código fonte e executado por um programa de computador chamado de interpretador que em seguida e executado pelo sistema operacional ou processador

### Portugol
é uma pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independente de linguagem de programação e uma pseudolinguagem que permite ao programador pensar no problema em si e não no equipamento que irá executar o algoritmo.

~~~portugol
programa
{

funcao inicio()
{
real nota1, nota2, nota3, nota4, media cadeia aluno

escreva ("Digite o nome do aluno: ")

leia(aluno)

escreva("Digite a nota 1:")

leia(nota1)

escreva ("Digite a nota 2:")

leia(nota2)

escreva("Digite a nota 3:")

leia(nota3)

escreva ("Digite a nota 4:")

leia(nota4)

media = (nota1+nota2+nota3+nota4)/4

escreva(" o aluno:" + aluno + " obteve a média: " + media)

}
}
~~~~

Exercício final 

~~~portugol
programa
{

funcao inicio()
{
real janeiro, fevereiro, marco, abril, total, media
cadeia vendedor

escreva ("Digite o nome do vendedor: ")

leia(vendedor)

escreva("Digite a vendas de janeiro:")

leia(janeiro)

escreva ("Digite a vendas de fevereiro:")

leia(fevereiro)

escreva("Digite a vendas de marco:")

leia(março)

escreva ("Digite a vendas de abril:")

leia(abril)

total = (janeiro+fevereiro+marco+abril)

media = total/4

escreva(" o vendedor: " + vendedor + " obteve o total de vendas de janeiro a abril de R$ " + total + "e a media de vendas desses meses são de " + media)

}
}
~~~~
## Desvios condicionais e boas práticas em programação ( comentários )

utilização da palavra reservada 'se', a condição a ser testada entre parênteses e as instruções que devem ser executadas entre chaves caso o desvio seja verdadeiro.

observação palavras reservada não pode ser usada para virar variável cada linguagem tem suas palavras reservadas

exemplo:
~~~portugol
se (media>=7) {
 escreva("parabéns!! você foi aprovado!!")
}
~~~~

exemplo 1
~~~portugol
programa
{

funcao inicio()
{
real nota1, nota2, nota3, nota4, media cadeia aluno

escreva ("Digite o nome do aluno: ")

leia(aluno)

escreva("Digite a nota 1:")

leia(nota1)

escreva ("Digite a nota 2:")

leia(nota2)

escreva("Digite a nota 3:")

leia(nota3)

escreva ("Digite a nota 4:")

leia(nota4)

media = (nota1+nota2+nota3+nota4)/4

escreva ("Sua média é: " + media)

se (media>=7) {
 escreva("\n" + "parabéns!! você foi aprovado!!")
}
}
}
~~~

#### se-senao
agora vamos imaginar que se a condição for falsa um outro conjunto de comandos deve ser executado quando iremos encontrar erra situação
~~~portugol
se (media>=7) {
 escreva("parabéns!! você foi aprovado!!")
}
senao{
escreva("infelizmente você foi reprovado")
}
~~~
 exemplo 2
~~~portugol
programa
{

funcao inicio()
{
real nota1, nota2, nota3, nota4, media cadeia aluno

escreva ("Digite o nome do aluno: ")

leia(aluno)

escreva("Digite a nota 1:")

leia(nota1)

escreva ("Digite a nota 2:")

leia(nota2)

escreva("Digite a nota 3:")

leia(nota3)

escreva ("Digite a nota 4:")

leia(nota4)

media = (nota1+nota2+nota3+nota4)/4

escreva ("Sua média é: " + media)

se (media>=7) {
 escreva("\n" + "parabéns!! você foi aprovado!!")
}
senao{
escreva("\n" + "infelizmente você foi reprovado")
}
}
}
~~~
exemplo 3
~~~portugol
//função do algoritmo: calcular a média aritimetica
//Autor: NowaDraco

programa
{

funcao inicio()
{
real nota1, nota2, nota3, nota4, media cadeia aluno

escreva ("Digite o nome do aluno: ")

leia(aluno)

escreva("Digite a nota 1:")

leia(nota1)

escreva ("Digite a nota 2:")

leia(nota2)

escreva("Digite a nota 3:")

leia(nota3)

escreva ("Digite a nota 4:")

leia(nota4)

media = (nota1+nota2+nota3+nota4)/4

escreva ("Sua média é: " + media)
//verifica se a média e maior ou igual a 7
se (media>=7) {
 escreva("\n" + "parabéns!! você foi aprovado!!")
}
//caso a média seja menor que 7
senao{
escreva("\n" + "infelizmente você foi reprovado")
}
}
}
~~~

### desvio condicional - caso
Este comando e similar aos comandos se e senao, e reduz a complexidade na escolha de diversas opções apesar de suas similaridades com e se ele possui algumas diferenças. neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos

exemplo 4
~~~portugol
programa
{
funcao inicio()
{
escreva("1 - Abrir Netflix" + "\n" + "2 - Abrir Amazon Prme" + "\n" + "3 - Abrir HBO GO" + "\n" + "4 - Sair")
inteiro menu = 0
escreva("\n" + "Sua opção::  ")
leia (menu)

se (menu==1){
escreva("\n" + "ok abrir Netflix!!")
}

se (menu==2){
escreva("\n" + "ok abrir Amazon Prime!!")
}

se (menu==3){
escreva("\n" + "ok abrir HBO GO!!")
}

se (menu==4){
escreva("\n" + "Saindo do menu.......")
}
}
}
~~~
exemplo caso
~~~portugol
programa
{
funcao inicio()
{
escreva("Esolha uma das opções:" + "\n" + "1 - Abrir Netflix" + "\n" + "2 - Abrir Amazon Prme" + "\n" + "3 - Abrir HBO GO" + "\n" + "4 - Sair")
inteiro menu = 0
escreva("\n" + "escolha a sua opção: ")
leia(menu)

escolha (menu)
{
caso 1:  //testa se o valor é igual a 1
escreva ("ok! abrir Netflix!!")
pare

caso 2:  //testa se o valor é igual a 2
escreva ("ok! abrir Amazon Prime!!")
pare

caso 3:  //testa se o valor é igual a 3
escreva ("ok! abrir HBO GO!!")
pare

caso 4:  //testa se o valor é igual a 4
escreva ("Saindo do menu.....")
pare

caso contrario:
escreva("Você deve escolher as opções 1,2 ou 3")

}
}
}
~~~

### Trabalhando com laços de repetição em Portugol

dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos , de acordo com uma condição ou com um contador.

Exemplo
~~~portugol
programa
{
funcao inicio()
{
inteiro contador, limite, resultado
contador = 0
limite = 10
faca
{
resultado = 9* contador 
escreva ("9 x " + contador + "=" + resultado + "\n")
contador ++
} enquanto ( contador <= limite)
}
}
~~~
exercício 1
~~~portugol
programa
{
funcao inicio()
{
inteiro contador, limite, numero, resultado

contador = 0
limite = 10

escreva("qual a tabuada você quer saber o resultado?" + "\n")
leia (numero)

faca
{
resultado = numero * contador 
escreva (numero + " x " + contador + "=" + resultado + "\n")
contador ++
} enquanto ( contador <= limite)
}
}
~~~
exercício 2
~~~portugol
programa
{
funcao inicio()
{
inteiro contador, limite, numero, resultado

contador = 0

escreva("qual a tabuada você quer saber o resultado?" + "\n")
leia (numero)

escreva("até qual número que que multiplique a tabuada?" + "\n")
leia (limite)

faca
{
resultado = numero * contador 
escreva (numero + " x " + contador + "=" + resultado + "\n")
contador ++
} enquanto ( contador <= limite)
}
}
~~~

### Aplicação prática com matrizes e vetores

uma matriz é uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória. 
a individualização de cada variável de um vetor é feita através do uso de índices 
os vetores são matrizes de uma só dimensão 

>cadeia Vetor[5]; // declara um vetor de 5 posições
cadeia Matriz[5][3]; // declara uma matirz de 5 linhas e 3 colunas

>cadeia frutas[4]
frutas[0]="maçã"
frutas[1]="Pera"
frutas[2]="Uva"
frutas[3]="Melão"
escreva(frutas[2])

>cadeia cesta[][] = {{"Maçã","100"},{"Pera","200"},{"Melão","300"}}
escreva ("fruta" + cesta[0][0] + "quantidade: " + cesta [0][1])


Exemplo 1
~~~portugol
programa
{
	funcao inicio ()
	{

cadeia frutas[4]
inteiro contador = 0

frutas[0]="maçã"
frutas[1]="Pera"
frutas[2]="Uva"
frutas[3]="Melão"
escreva(frutas[2])

faca{ escreva (frutas[contador] + "\n")
contador++

}
enquanto (contador<=3)

	}
}
~~~
exemplo 2
~~~portugol
programa
{
	funcao inicio ()
	{

cadeia cesta[][] = {{"Maçã","100"},{"Pera","200"},{"Melão","300"}}
escreva ("fruta" + cesta[0][0] + "quantidade: " + cesta [0][1])

	}
}

programa

{
	funcao inicio ()
	
	{
inteiro contador=0
cadeia cesta[][] = {{"Maçã","100"},{"Pera","200"},{"Melão","300"}}

faca{

escreva (" produto: " + cesta[contador][0] + " quantidade: " + cesta[contador][1] + "\n")
contador++

}enquanto (contador<=2)
	
}
}
~~~
Exercício
~~~portugol
programa

{
	funcao inicio ()
	
	{
inteiro contador=0
cadeia cesta[][] = {{"João","São Paulo", "(11) 9999-5241"},{"Maria","Ribeirão Preto","(16) 9999-8596"},{"Ana","Manaus","(92) 9999-8574"}}

faca{

escreva (" Nome: " + cesta[contador][0] + " Cidade: " + cesta[contador][1] + " Tel." + cesta[contador][2] + "\n")
contador++

}enquanto (contador<=2)
	
}
}
~~~
