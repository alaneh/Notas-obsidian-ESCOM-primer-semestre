# Curso de programación C
```C
#include <stdio.h>
/*
En un supermercado por la cuarentena quieren disminuir los precios
al 15% para ayudar a las personas y que no se queden los productos en
la tienda.
Debes dar el precio y el programa debe dar los precios con el descuento y el 
descuento.
*/
int main(){
	float precio, descuento, precioDescuento;
	printf("Dame el precio del producto\n");
	scanf("%f",&precio);
	descuento = precio * 0.15;
	precioDescuento = precio - descuento;
	printf("El nuevo precio del producto es %f", precioDescuento);
	printf("\nEl descuento fue de %f", descuento);
	
	return 0;
}

```