# votacion
#include "stdafx.h"
#include <iostream>
#include "conio.h"
using namespace std;
void main () 
{int edad;
 cout <<"ingrese la edad: ";
 cin >> edad;
 if(edad>=18)
	 cout<<"puede votar";
 else 
	 cout<<"no puede votar";
 getch();
}
