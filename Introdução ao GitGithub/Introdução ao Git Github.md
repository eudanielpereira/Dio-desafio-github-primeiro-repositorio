# Módulo 1 - Introdução ao Git/Github (Otávio Reis)

Todas as anotações foram retiradas ou desenvolvidas baseadas nas aulas da plataforma DIO.



### Navegação via command line interface e instalação

#### Comandos básicos para um bom desempenho no terminal

Comandos de operação no Windows:

* listar: dir
* navegar entre as pastas: cd /
* navegar para uma pasta específica: cd nome da pasta
* voltar: cd ..
* limpar o terminal: cls
* TAB auto completa as palavras (atalho)
* criar pasta: mkdir
* deletar arquivos de uma pasta: del nome da pasta
* remover repositório: rmdir nome da pasta



### Entendendo como o Git funciona por baixo dos panos

#### Tópicos fundamentais para entender o funcionamento do Git

A sigla SHA significa Secure Hash Algorithm, é um conjunto de funções de hash criptográficos projetados pela NSA (Agência de Segurança Nacional dos EUA).



#### Objetos Internos do Git

* Blobs: é uma coleção de dados armazenados
* Trees: armazena os blobs, guarda a estrutura dos blobs
* Commit: armazena tudo, informações sobre os arquivos e os arquivos



#### Chave SSH

Forma de estabelecer uma conexão segura entre as máquinas.



### Primeiros comandos com o Git

* Git init
* Git add
* Git commid



#### 	Ciclo de vida dos arquivos no Git

* Git init: cria um repositório

  

* Tracked: arquivos que o Git tem ciência dele. É dividido em três etapas:

  * Unmodified: não modificado
  * Modified: modificado
  * Staged: arquivo que está "esperando para entrar no palco"

* Untracked: arquivos que o Git não tem conhecimento sobre ele.



* Repositório: 
  * remote repository: servidor
  * working repository, stagin area e local repository: ambiente de desenvolvovimento



* Git status: mostra o status do arquivo



Working repository -> **Git add** -> Stagin area -> **git commit -m** -> local repository



### Resolvendo conflitos

* Git add *



* Git pull origin master/main: é utilizado quando há versões diferentes e dá erro ao subir para o Github. Ele vai dizer onde está o erro.



* Git clone link: clona um repositório do Github.









 

