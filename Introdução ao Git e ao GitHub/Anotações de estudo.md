# Introdução ao Git e ao GitHub #

## Entendendo o que é Git e sua importância ##

**Git** é um software desenvolvido em 2005, por Linus Torvalds, para a construção de projetos, como sites, códigos ou softwares, onde vários desenvolvedores podem trabalhar ao mesmo tempo. Sua funcionalidade é o seu sistema de controle de alterações. Quando alguém muda o código, por exemplo, é gerada uma nova versão do projeto, sem ter o risco de perder qualquer informação. E todas as versões são salvas em um repositório.

**GitHub** é uma rede social para desenvolvedores

* Controle de versão

* Armazenamento em nuvem

* Trabalho colaborativo

* Melhorar seu código

* Reconhecimento

  

## Comandos básicos para um bom desempenho no terminal ##

**Windows**

* cd (Navega para um diretório específico)

* dir (Lista os diretórios presentes no diretório atual)

* ls (Exibir arquivos/diretórios)

* mkdir (Cria um novo diretório)

* del / rmdir (Deletar arquivos / Deletar o repositório + arquivos)      


**O Git Bash é um terminal extendido para otimizar o uso do Git.**   

  
 ## Entendendo como o Git funciona por baixo dos panos ##

  
 ### Tópicos fundamentais para entender o funcionamento do Git ###    

  
 * SHA1	O SHA1 (Secure Hash Algorithm)é um conjunto de funções hash criptográficas. A  encriptação gera um conjunto de characteres identicador de 40 dígitos, usado para  codificar e proteger os nossos arquivos.

 * Objetos Fundamentais

 * Sistema Distribuído 

 * Segurança  

  
### Objetos internos do Git ###  

* Blobs
* Trees
* Commits (Commit é muito difícil de ser alterado ou manipulado) 

  
### Chave SSH e Token ###

Chave SSH - Forma de estabelecer uma conexão segura e criptada entre duas máquinas .

Token- é uma chave que permite ter acesso a algo.


### Primeiros comandos com Git ###

**Iniciando o Git e criando um commit**

* Git init (repositório)

* Git add * (adiciona arquivo)

* Git commit (cria commit)

  
### Ciclo de vida dos arquivos no Git ###

**Passo a passo no ciclo de vida**

* Untracked (Working directory)

* Unmodified (Staging area)

* Modified

* Stagead (Local repository)


## Introdução ao GitHub ##

### Trabalhando com o GitHub, alguns comandos ###

* git remote add origin

 * git remote -v

* git status (para verificar se um arquivo já está em staged)

* git commit -m "mensagem"

* git push origin master (para enviar ao GitHub)

* git pull origin master (para puxar do GitHub)


## Resolvendo Conflitos ##

### Como os conflitos acontecem no GitHub e como resolvê-los ###

Conflito de Mergi - quando o GitHub tenta juntar as alterações

Quando der o conflito é preciso identificá-lo.

* git add *

* git commit -m "resolve conflitos"





  

