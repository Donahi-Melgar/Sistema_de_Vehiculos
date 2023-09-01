# Sistema_de_Vehiculos
Crea un sistema que modele diferentes tipos de vehículos, como automóviles y bicicletas. Cada vehículo debe tener la capacidad de acelerar y frenar. Además, para los automóviles, también se debe registrar la cantidad de pasajeros que pueden llevar.

Define una interfaz llamada Conducible con los siguientes métodos:

void acelerar(int velocidad)
void frenar()
Crea una clase base abstracta llamada Vehiculo que implemente la interfaz Conducible. Esta clase debe contener un campo para el nombre del vehículo y un constructor que acepte el nombre.

Crea dos clases derivadas de Vehiculo:

Automovil: Debe tener un campo para la cantidad máxima de pasajeros y un constructor que acepte el nombre del vehículo y la cantidad de pasajeros.
Bicicleta: No necesita campos adicionales.
Implementa los métodos acelerar y frenar en cada una de las clases derivadas. Puedes imprimir mensajes simples para indicar que el vehículo está acelerando o frenando.

En el método main, crea instancias de diferentes tipos de vehículos y demuestra cómo se pueden acelerar y frenar.
