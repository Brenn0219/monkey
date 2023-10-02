# Lexer

O analisador lexico conhecido como *lexer* analisa caracter por caracter identificando e gerando os tokens, sua estrura e composta por:

* input - string para analisar
* positon - ponteiro para posicao atual da string
* readPosition - ponteiro para a proxima posicao a ser lida
* ch - caracter atualmente sendo lido

`NextToken()` e o metodo principal onde analisamos toda o codigo e identificando os tokens. Este metodo e composto outros metodos como `skipWhitespace()` para ignorar os espacos, `newToken()` gera uma estrutura de token assim que identifica um, `isLetter()` e `isDigit()` verifica se e letra e numero e `readChar()` que le o proximo caracter do codigo que esta sendo analisado.