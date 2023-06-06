# c-
numero veradero y falso


#include <iostream>

using namespace std;



int main() {

 int num_entradas;

 int positivos = 0;

 int negativos = 0;

 int ceros = 0;



 // pedir al usuario el numero de entradas

 cout << "ingrese el numero de entradas: ";

 cin >> num_entradas;



 for (int i = 0; i < num_entradas; i++) {

     double entrada;

     cout << "ingrese una entrada: ";

     cin >> entrada;



     if (entrada > 0) {

         positivos++;

     } else if (entrada < 0) {

         negativos++;

     } else {

         ceros++;

     }

 }

 // impimir los resultados

 cout << "cantidad de entradas positivas: " << positivos << endl;
    cout << "cantidad de entradas negativas: " << negativos << endl;

    cout << "cantidad de entradas iguales a cero: " << ceros << endl;

}
