# ChallengeJava | Conversores | AluraLatam
 
## 1. DESCRIPCIÓN

Aplicacion de Java que extiende la clase JFrame para crear una interfaz gráfica de usuario. La aplicación permite al usuario elegir entre dos conversores: *Conversor de divisas y Conversor de temperatura.*

## 2. FUNCIÓN

### Ventana Principal
La interfaz gráfica de usuario es creada con la biblioteca de Java Swing y cuenta con dos botones: **"Continuar" y "Cerrar"**. El usuario puede elegir entre dos opciones de conversión utilizando un JComboBox: *"Conversor de Divisas" y "Conversor de Temperatura"*. Al presionar el botón "Continuar", el programa lleva al usuario a la ventana correspondiente a la opción seleccionada. 

Al presionar el botón "Cerrar", se muestra un cuadro de diálogo de confirmación antes de cerrar la aplicación. En caso de una excepción, se muestra un cuadro de diálogo de error.


### Conversor de Divisas
Al seleccionar la primera opción se abre una nueva ventana (Convertidor de Divisas) que permite convertir una cantidad de una moneda a otra, elegida por el usuario, de una lista de seis monedas disponibles.

Contiene dos campos de texto para ingresar el monto a convertir y dos JComboBox para elegir la moneda de base y la moneda a convertir.

Contiene dos botones, uno para **CONVERTIR** y otro para **REGRESAR** a la ventana principal.

### Conversor de Temperatura
Al seleccionar la segunda opción se abre una nueva ventana (Convertidor de Temperaturas) que permite convertir entre tres unidades de temperatura: *Celsius, Fahrenheit y Kelvin*.

Interfaz gráfica de usuario (GUI) amigable y fácil de usar.

Valida y muestra un mensaje de error si el usuario ingresa una cantidad inválida.

---

## 3. EJECUCIÓN
Para ejecutar la aplicación, se necesitan las siguientes bibliotecas externas:
*  javax.swing
*  java.awt

Ejecute la clase principalframe para iniciar la aplicación.
