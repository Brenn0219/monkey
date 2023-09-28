# Escrevendo um Interpretador em Go

Toda linguagem de progração para ser desenvolvida precisa de um interpretador ou um compilador, sem isso ela é só um "texto" sem ser compreendido. A linguagem desenvolvida nesse projeto é chamada de Monkey, uma lista de recursos que a linguaguem possui:

* sintaxe semelhante a C
* liguações de variáveis 
* expressões aritméticas 
* funções integraddas
* funções de primeira classe e de ordem superior
* closures
* uma estrutura de dados de string
* uma estrutura de dados de matriz
* uma estrutura de dados de hash

O interpretador desenvolvido implementa todos esses recursos. Ele vai tokenizar e analisar o código-fonte do Monkey em REPL e terá algumas partes principais como: 

* lexer
* parser (analisador)
* árvore de sintaxe abstrata (AST)
* sistema de obejtos internos
* avaliador 