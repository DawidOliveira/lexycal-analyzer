1 - Executar o analisador léxico gerando o lex.yy.c:
	flex lexico.l

2 - compilando o arquivo gerado pelo flex:
	g++ lex.yy.c -lfl -o lexico
	
3 - Iniciando análise lexa:
	./lexico main.c main.lex
