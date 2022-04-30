# Módulo 1 - Lógica de programação essencial (Denilson Bonatti)

Todas as anotações foram retiradas ou desenvolvidas através das aulas na plataforma DIO.

## Introdução ao Portugol

### Aprenda como utilizar uma estrutura de repetição

**Estrutura de repetição**, dentro da lógica de programação, é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.



### O que são linguagem de programação

**Linguagem de programação** é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (softwares). Um software pode ser desenvolvido para rodar em um computador, dispositivo móvel ou em qualquer equipamento que permita sua execução.

A função da linguagem de programação é servir de um meio de comunicação entre computadores e humanos.



* Alto nível: a sintaxe se aproxima mais da nossa linguagem e ser distanciam mais da linguagem da máquina.
* Baixo nível: é aquela que se aproxima mais da linguagem da máquina.



* Compilados: o código fonte é executado diretamente pelo sistema operacional ou processador, após ser traduzido por meio de um processo chamado compilação.
* Interpretados: o código fonte é executado por um  programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional.

#### Portugol

**Portugol** é uma pseudolinguagem que permite ao leitor desenvolver algoritmos de forma simples e intuitiva, independentemente de linguagem de programação.

* Prática: 
  * Para aparecer algo escrito: **escreva(...)**.
  * Quando colocar números é necessário informar se é **inteiro** ou **real**.
  * **caracter** é usado para receber uma letra de A a Z.
  * **cadeia** é utilizado para receber mais de uma letra.
  * **leia(...)** pede para o usuário inserir uma informação.
  * Concatenar no Portugol Studio: **+**.



### Aprenda a utilizar desvios condicionais e boas práticas de programação

**Desvio condicional se**: é utilizada a palavra reservada SE, a condição a ser testada deve estar entre () e as instruções devem ser executadas entre {}, caso o desvio seja positivo.

Ex.: se(media>=7){

​			escreva("Parabéns!")

}

**Se - senão**: condição falsa (deve ser escrito abaixo da condição verdadeira, após a chave fechada).

Ex.: senao {

​		escreva("Você foi reprovado.")

}



* Prática:
  * Quebra de linha: **\n**



**Comentário**: utilizado para relembrar algo sobre o código, dar explicações ou instruções. É feito geralmente no início.

Deve ser colocado depois de //, que demostra que o texto não é código.



**Desvio condicional caso**: é similar ao se e senão, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o SE, ele possui algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos.



### Laços de repetição em Portugol

**Laço de repetição** é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos com uma condição ou contador.



* Prática:
  * contador ++ = contador +1



### Aplicação prática com matrizes e vetores

**Matriz** é uma coleção das variáveis de mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória.

A individualização de cada variável de um vetor é feita através do uso de índice.

Os **vetores** são matrizes de uma só dimensão.