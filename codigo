include <stdio.h>
#include <stdlib.h>
#include <locale.h>

main(){
	setlocale(LC_ALL,"Portuguese");
	
	int i;
	int termo,penultimo = 1;
	int ultimo = 0;
	printf("0,");
	for(i=1;i <=7;i ++){
		termo = ultimo + penultimo;
		penultimo = ultimo;
		ultimo = termo;
		printf("%d,",termo);
	}
}
