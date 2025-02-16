# Actividad evaluable | Diagramas de casos de usos | José Luis Salado Horta 

## 1. Crea el diagrama de uso haciendo uso de platuml, representado los actores y casos de uso que identifiques en los requisitos.
![image](https://github.com/user-attachments/assets/845ddc00-4cdc-47c8-a7de-bc76e26b447f)

## 2. Describe, haciendo uso de la plantilla, al menos el caso de uso "Sacar dinero", con las interacciones que tiene entre el actor y el caso de uso.

Nombre: Sacar dineroActor: ClienteDescripción: Este caso de uso describe cómo un cliente puede retirar dinero de un cajero automático. Para ello, primero debe identificarse correctamente en el sistema y asegurarse de que tiene saldo suficiente. Además, el sistema comprobará que el monto solicitado no supere el límite diario de retiro.

¿Qué necesita cumplirse antes?Antes de poder sacar dinero, el cliente tiene que haber iniciado sesión en el cajero y su cuenta debe tener fondos suficientes. También hay un límite diario de retiro que no se puede superar.

¿Cómo funciona el proceso?

El cliente elige la opción "Sacar dinero" en el cajero automático.

El sistema le pide que ingrese la cantidad de dinero que quiere retirar.

El cliente introduce el monto deseado.

El cajero verifica si la cuenta tiene suficiente saldo.

Si hay saldo suficiente, se revisa si el monto solicitado supera el límite diario.

Si todo está en orden, el cajero entrega el dinero y actualiza el saldo de la cuenta.

Finalmente, el sistema le da la opción de imprimir un recibo con los detalles de la operación.

¿Qué pasa si algo no va bien?

Si el cliente no tiene suficiente dinero en su cuenta, el sistema le avisará y le pedirá que ingrese un monto menor.

Si el monto supera el límite diario de retiro, el cajero le indicará que debe elegir una cantidad menor.

## 3. Responde a las siguiente pregunta:¿Para qué me sirve tener/realizar un diagrama de casos de uso modelando el sistema que se representa? ¿Qué aporta?

Un diagrama de casos de uso es como un mapa que nos ayuda a entender cómo funciona un sistema antes de construirlo. Es una forma sencilla de ver qué puede hacer una persona (o usuario) dentro del sistema y qué reglas se deben seguir.

Este tipo de diagrama es muy útil porque ayuda a que todas las personas que trabajan en el proyecto, como programadores, diseñadores y clientes, se pongan de acuerdo en lo que se necesita hacer. También permite detectar errores o cosas que faltan antes de empezar a programar, lo que ahorra tiempo y evita problemas en el futuro. Además, sirve como una guía para que los desarrolladores sepan cómo deben funcionar las distintas partes del sistema, asegurando que todo esté bien organizado y claro desde el principio.
