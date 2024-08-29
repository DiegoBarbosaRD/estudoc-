# estudoc-
estudo unip c++


#include <locale.h>

 int main(void){
 	setlocale(LC_ALL, "portuguese");
 	int idade, doenca;
 	printf("digite sua idade: \n");
 	scanf("%", &idade);
 	
 	if(idade >= 18){
 		printf("está doente? se sim digite 1, senão, digite 0: \n");
 		scanf("%d", &doenca);
 		
 		if(doenca){
 			printf("nada de doar. \n");
 			
 		
		 }
		 else{
		 	printf("dos si zé. \n");
		 	
		 }
	 }
 else{
 	printf("você é menor de idade, nada de doar. \n");
 	
 }
 return 0;
}
 
 
