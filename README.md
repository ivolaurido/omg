#include <stdio.h>
int main()
{
 int eleccion,a,b,c;
 printf("-bienvenido a la montaña de las preguntas yo soy el mago de de la montaña\n");
 printf("-vos sos...\n");
 printf("a-elfo\n");
  printf("b-orco\n");
printf("c-dragon\n");
 scanf("%d", & eleccion);
 eleccion = getchar();
 //este switch es para elegir la falsa raza
    switch(eleccion) {
    
 case 'a'  :
      printf("-de ahora en adelante seras un elfo (hasta que reinicies el juego)");
    break;
	
  case 'b'  :
      printf("-de ahora en adelante seras un orco (hasta que reinicies el juego)");
      break; 
	  case 'c' :
      printf("-de ahora en adelante seras un dragon (hasta que reinicies el juego)");
      break;
  
      default : 
      do{
    printf("-son tres opciones nomas podes elegir bien?\n");
    scanf(" "); 
 
   } while(eleccion !=a ||eleccion !=b || eleccion!=c );
   
}
printf("\n-si deseas superar la montaña de las preguntas deberas responer 11 de 20 preguntas correctamente\nde lo contrario quedaras atrapado en esta hasta el fin de tus dias\n");
  printf("-\n");
     scanf(" ");
   return 0;
}
