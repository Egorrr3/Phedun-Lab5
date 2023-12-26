bison -yd parser.y
flex lexer.l
gcc -lm y.tab.c -std=c99 -w
a < input.c