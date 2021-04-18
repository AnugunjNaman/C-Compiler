Compiling goes as follows:  
  bison -d parser.y <br>
  flex lexer.l<br>
  gcc lex.yy.c parser.tab.c <br>
  ./a.out full_example.txt <br>
