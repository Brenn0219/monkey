# REPL

O REPL (Read Eveal Print Loop) lê a entrada do usuário, tokeniza-a usando um lexer e, em seguida, imprime os tokens resultantes. 
No código `repl.go` ele lê a entrada a partir do recurso de entrada até encontrar uma nova linha, pega a linha recém-lida e a passa para uma instância do lexer, e, finalmente imprime todps os tokens que o lexer nos fornece até encontrar o token de final de arquivo (EOF).