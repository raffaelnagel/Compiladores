int main(int argc, char **argv)
{
    int s;
    yyin = fopen("out.c","r");
    while(running != 0) 
    {
	s = yylex();
    	printf("linha %d token %d\n", lineNumber, s);
    }
    hashPrint();
    return 0;
}
