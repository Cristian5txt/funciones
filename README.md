#include <iostream>

using namespace std;

float sumar (float a, float b);
float restar (float a, float b);
float multiplicar (float a, float b);
float divisor (float a, float b);
int main()
{


    float x,y,resultado_suma,resultado_resta,resultado_multiplicacion,resultado_divison;

        cout << "INGRESE EL VALOR DE x" << endl;
        cin>>x,
        cout << "INGRESE EL VALOR DE y" << endl;
        cin>>y;

        resultado_suma = sumar(x,y);
        resultado_resta = restar (x,y);
        resultado_multiplicacion = multiplicar (x,y);
        resultado_divison = divisor (x,y);


    cout << "lA SUMA ES: " <<resultado_suma<< endl;
    cout << "lA RESTA ES: " <<resultado_resta<< endl;
    cout << "lA MULTIPLICACION ES: " <<resultado_multiplicacion<< endl;
    cout << "lA DIVISION ES: " <<resultado_divison<< endl;


    return 0;
}
    float sumar (float a, float b){
    float suma = a+b;
    return suma;

    }
    float restar (float a, float b){
    float resta = a-b;
    return resta;

    }
    float multiplicar (float a, float b){
    float multiplicacion = a*b;
    return multiplicacion;

    }
    float divisor (float a, float b){
    float division = a/b;
    return division;

    }
