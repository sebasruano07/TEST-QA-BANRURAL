Los errores con los cuales contaba el código eran sencillos para afectaban gran parte la funcionalidad de la aplicación, estos errores pueden ser resueltos de la siguiente manera:

Para limitar el ingreso de algún otro tipo de carácter que no sea número debemos de volver el input a un tipo number.

Otro error con el que contaba este código era al momento de crear los números enteros ya que lo que realizaba dicha instrucción eran números flotantes.

La variable ATTEMPS, la cual es la encarga de los intentos permitidos para la aplicación, se encontraba incorrecta porque solo nos permitía 5 intentos.

En la constante llamada lowOrHi hacía falta colocar un punto en la instrucción document.querySelector.

En la variable llamada userGuess tuve la necesidad de realizar una transformación de un string a un float con el objetivo de poder comparar el número creado aleatoriamente y el número ingresado por el usuario.

Se realizaron cambios a la hora de sumar el intento del usuario y mostrar en pantalla el número ingresado debido a que no están permitidos los números flotantes, a la hora que un usuario ingrese un número flotante no se le mostrará dicho número, no sumará un intento y aparecerá un aviso explicándole las razones.

Las instrucciones en el if que evaluaba hoy el número ingresado por el usuario y el número creado aleatoriamente se encontraban al revés ya que se analizaban los intentos con el número ingresado al usuario y el número creado aleatoriamente con el contador de intentos.

Al momento de mostrar algún texto, como por ejemplo incorrecto, poseían un color hoy que no les pertenecía, por lo tanto, sólo se debía ordenar dichos colores.

El programa aceptaba números mayores a 100, por lo cual se creo una variable con el número 100 y se creo un nuevo if para evaluar esta sentencia y no aceptar números mayores a 100

Se creó un if adicional con el objetivo de verificar que el número ingresado por el usuario realmente sea un entero.

Se corrigió la instrucción llamada addEventListener, esta se encontraba mal escrita porque poseía la e en minúscula en las dos llamadas que poseía en el código.

El último error que se encontró fue en la función resetGame(), esta contaba con un error muy parecido porque esta contenía una variable la cual creaba números enteros pero contaba con el problema de que solo nos mostraba el número 1.

Para poder evitar estos errores y no enviarle al tester una aplicación que no es funcional, el programador de realizarle ciertas pruebas con el objetivo de entregarle al tester una aplicación funcional procurando que no contenga errores.