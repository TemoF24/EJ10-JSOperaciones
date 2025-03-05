# README - Calculadora Simple

## Descripción
Este es un ejemplo de una calculadora simple desarrollada con HTML, CSS y JavaScript. Permite realizar operaciones básicas de matemáticas: suma, resta, multiplicación y división. La interfaz es sencilla y está diseñada para ser intuitiva, con un diseño limpio y accesible. Los usuarios pueden ingresar dos números y seleccionar una operación para obtener el resultado.

## Estructura del código

1. **HTML**
   - El código HTML crea una interfaz de usuario con dos campos de entrada donde los usuarios pueden ingresar dos números. 
   - Hay botones para realizar las operaciones: sumar, restar, multiplicar y dividir.
   - El resultado de la operación seleccionada se muestra en la parte inferior de la calculadora.

2. **CSS**
   - El estilo se utiliza para dar formato y mejorar la apariencia de la calculadora. La calculadora está centrada en la página, con un fondo blanco y una sombra suave para darle un aspecto de tarjeta.
   - Los botones tienen un diseño con bordes redondeados y un cambio de color al pasar el cursor por encima para mejorar la experiencia del usuario.
   - Las entradas para los números tienen un borde sutil y un estilo uniforme.

3. **JavaScript**
   - El script contiene las funciones necesarias para realizar las operaciones matemáticas:
     - **sumar()**: Suma los dos números introducidos y muestra el resultado.
     - **restar()**: Resta el segundo número del primero y muestra el resultado.
     - **multiplicar()**: Multiplica ambos números y muestra el resultado.
     - **dividir()**: Divide el primer número por el segundo y muestra el resultado. Si el segundo número es 0, muestra un mensaje de error.
   - Si el usuario no ingresa números válidos, se muestra un mensaje indicando que deben ingresar valores correctos.

4. **Validación de entradas**
   - Las funciones comprueban si los valores ingresados son números válidos utilizando `isNaN()`.
   - En el caso de la división, también se verifica que el divisor no sea cero, evitando el error de división entre cero.

## Estilos y diseño

- **Colores:**
  - El fondo de la calculadora es blanco, mientras que el fondo de los botones es verde.
  - Los botones cambian de color a un verde más oscuro cuando el cursor pasa por encima.
  
- **Tipografía:** La fuente predeterminada utilizada es "Arial", que es comúnmente compatible con todos los navegadores.

- **Botones y entradas:** Los botones y entradas tienen bordes redondeados y un diseño limpio y sencillo para mejorar la experiencia del usuario.

## Instrucciones de uso

1. Abre el archivo `.html` en tu navegador para ver la calculadora en acción.
2. Ingresa dos números en los campos de entrada.
3. Haz clic en uno de los botones de operación (Sumar, Restar, Multiplicar, Dividir) para ver el resultado.
4. Si intentas dividir entre 0 o ingresas valores no válidos, el programa mostrará un mensaje de error adecuado.

## Contacto

Si tienes preguntas o deseas sugerir mejoras, no dudes en contactarnos. Puedes adaptar o mejorar este código para tus propios proyectos de calculadora.

