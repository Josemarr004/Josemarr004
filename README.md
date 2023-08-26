'''c++'''
# conversor de centimetros en c++

#include <iostream>
using namespace std;

int main (){

    float metros, yardas, varas, pulgadas, pies,centimetros;
    int Opcion;
    float resultado;

    cout<< "bienvenido, al conversor de centimetros a las diferentes tipos de medida: " <<endl;
    cout<< "ingrese una opcion" <<endl;
    cout<< "1, metros: " <<endl;
    cout<< "2, yardas: " <<endl;
    cout<< "3,varas: " <<endl;
    cout<< "4, pulgadas:"  <<endl;
    cout<< "5, pies:" <<endl;

    cin>> Opcion;
      
    switch (Opcion)
    {
    case 1: 

        cout<< "centimetros a metros:" <<endl;
        cout<< "ingrese la cantidad de centimetros a convertir:" <<endl;
        cin>> centimetros; 
        metros = centimetros / 100;
        cout<< centimetros << " centimetros equivalen a " << metros << " metros: " <<endl;
        break;
    case 2: 
        cout<< "centimetros a yardas: " <<endl;
        cout<< "ingrese la cantidad de centimetros a convertir: " <<endl;
        cin>> centimetros;
        yardas = centimetros / 91.44;
        cout<< centimetros<< " centimetros equivalen a " << yardas << " yardas: " <<endl;
        break;
    case 3: 
        cout<< "centimetros a varas: " <<endl;
        cout<< "ingrese la cantidad de centimetros a convertir: " <<endl;
        cin>> centimetros;
        varas = centimetros / 84;
        cout<< centimetros<< " centimetros equivalen a " << varas << " varas: " <<endl;
        break;
    case 4: 
        cout<< "centimetros a pulgadas:" <<endl;
        cout<< "ingrese la cantidad de centimetros a convertir: " <<endl;
        cin>> centimetros;
        pulgadas = centimetros / 2.54;
        cout<< centimetros<< " centimetros equivalen a " << pulgadas << " pulgadas: " <<endl;
        break;
    case 5: 
        cout<< "centimetros a pies:" <<endl;
        cout<< "ingrese la cantidad de centimetros a convertir:" <<endl;
        cin>> centimetros;
        pies = centimetros / 30.48;
        cout<< centimetros<< " centimetros equivalen a " << pies << " pies: " <<endl;
        break;

    default:
        cout<< " que parte de que solo hay 5 opciones no entendiste .-. elige otra ";
        break;
    }

    return 0;
}


# conversor de centimetros en pseudocodigo

'''pseudocodigo'''

Algoritmo ConversorDEcentimetros

	definir  metros, yardas, varas, pulgadas, pies, centimetros como real 

	definir opcion  como entero 

	escribir " bienvenido, al conversor de centimetros a las diferentes tipos de medida"	

	escribir "ingrese una opcion "

	escribir "1-. metros "

	escribir "2.- yardas"

	escribir "3.- varas"

	escribir "4.- pulgadas"

	escribir "5.- pies"
    
	leer opcion

	si opcion = 1 entonces escribir "centimetros a metros"
		escribir "ingrese la cantidad en centimetros a convertir"
		leer centimetros 
		metros = centimetros / 100
		escribir centimetros " centimetros equivalen a " metros " metros "
		fin si 

	si opcion = 2 entonces escribir "centimetros  a yardas"
		escribir "ingrese la cantidad en centimetros a convertir"
		leer centimetros 
		yardas = centimetros / 91.44
		escribir centimetros "equivalen a " yardas " yardas"
	fin si 

	si opcion = 3 entonces escribir " centimetros a varas"
		escribir "ingrese la cantidad en centimetros a convertir"
		leer centimetros 
		varas = centimetros / 84
		escribir centimetros "equivalen a " varas " varas "
	FinSi

	si opcion = 4 entonces escribir "centimetros a pulgadas "
		escribir "ingrese la cantidad en centimetros a convertir"
		leer centimetros 
		pulgadas = centimetros / 2.54
		escribir centimetros "equivalen a " pulgadas " pulgadas "
	FinSi
	
	si opcion = 5 entonces escribir " centimetros a pies "
		escribir "ingrese la cantidad en centimetros a convertir"
		leer centimetros 
		pies =  centimetros / 30.48
		escribir centimetros " equivalen a " pies " pies "
		
		
	sino escribir "  que parte de que solo hay 5 opciones no entendiste .-. elige otra opcion "
	FinSi


	
FinAlgoritmo
