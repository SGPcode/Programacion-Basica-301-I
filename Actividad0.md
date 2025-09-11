La estructura básica de un programa en C++ suele estar compuesta por los siguientes elementos:

Directivas de preprocesador:
Son instrucciones que le indican al compilador que incluya ciertos archivos o bibliotecas antes de compilar el programa. La más común es #include <iostream>, que permite la entrada y salida de datos.

Función principal (main):
Todo programa en C++ debe tener una función principal llamada main. Es el punto de inicio donde comienza la ejecución del programa.

Declaración de variables:
Dentro de la función main (o cualquier otra función), se pueden declarar variables que almacenarán datos utilizados por el programa.

Sentencias/instrucciones:
Son las acciones que realiza el programa, como operaciones aritméticas, entrada/salida de datos, condicionales, bucles, etc.

Valor de retorno:
Al finalizar, la función main devuelve un valor entero, normalmente return 0;, que indica que el programa terminó correctamente.

Ejemplo de estructura básica:

C++
#include <iostream> // Directiva de preprocesador

int main() { // Función principal
    int numero; // Declaración de variable
    std::cout << "Hola, ingresa un número: "; // Salida de datos
    std::cin >> numero; // Entrada de datos
    std::cout << "El número ingresado es: " << numero << std::endl;
    return 0; // Valor de retorno
}
