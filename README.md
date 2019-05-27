# Programacion-en-C
Estructuras secuenciales 

#include <stdio.h>
#include <stdlib.h>
int main()
{ 
 	int x,y,r; //definimos el nombre y tipo de dato de las variables que utilizaremos en todo el algoritmo
 	printf("Ingrese un numero: ");//funcion que nos permite mostrar un mensaje por pantalla 
 	scanf("%d%d",&x,&y);//funcion que nos permite capturar el mismo tipo de dato en la direccion de memoria de las variables definida pero que ambas sean del mismo tipo de dato 
 	r=x+y;//almacenamos la suma de la variable x,y en la variable r del tipo de dato entero
 	printf("la suma es: %d ",r);//mostramos el valor de la variable r que es la suma de x,y
}
