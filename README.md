#include <stdio.h> // Programa que leia um numero inteiro "n", e mostrar na tela a tabuada de n de 1 a 10.

main (){

	int n, i, produto; //Variavel n aloca o valor da tabuada; i aloca o valor que será multiplicado; produto aloca o resultado;
	
	printf ("Deseja a tabuada para qual valor? \n");
	scanf ("%d", &n);
	
	for (i = 1; i <= 10; i++){ //variavel i recebe 1; variavel i menor ou igual a 10; variavel i continua;
		produto = n * i; // multiplicação
		
		printf ("%d x %d = %d\n", n, i, produto); // resultado
		
	}
	
	return 0;
}
