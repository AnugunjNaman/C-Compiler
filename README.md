Compiling goes as follows:  
bison -d parser.y
flex lexer.l
gcc lex.yy.c parser.tab.c
./a.out full_example.txt