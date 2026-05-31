# sesion-11a

# Apuntes 26/05

Durante clases nos seguimos dedicando a trabajar en el proyecto 02 por lo que nos dedicamos a resolver el circuito de la opción 01, ya que trabajamos en éste el lunes 25 durante la mañana y logramos que funcionara, pero por alguna razón llegaba a un punto en el que dejaba de prender los LEDs y esto se solucionaba desconectando el cable que estaba en el ``reset`` del 4017, dejarlo interactuar con el aire por unos segundos y volver a conectarlo (o dejarlo en el aire) en donde debía ir XD no entendimos por qué sucedía esto y preferimos guardar las preguntas para la clase de hoy.

![Cable tomando su break para respirar](./imagenes/cable-respirando.png)

Antes de explicar la situación, Misa nos revisó el circuito y nos hizo las siguientes correcciones:

+ Añadir un capacitor de 100μF en el ``pin 5`` del chip 555
+ Arreglar la conexión entre el chip 555 y 4017, ya que estábamos utilizando el ``pin 3`` del 555 como salida y el ``pin 13`` del 4017 como entrada, siendo que tenemos que utilizar el ``pin 14`` del 4017 en vez del 13.
+ Unir el ``pin 13`` del 4017 a tierra mediante una resistencia de 100k

Luego de hacer estos cambios, el esquemático quedó de la siguiente manera:

![Esquemático actualizado](./imagenes/piezov03.jpg)

Con estos cambios el primer circuito quedó funcionando en la protoboard, por lo que nos dividimos el trabajo con nuestros compañeros y mientras unos armaban en la protoboard el segundo circuito, yo hacía cambios en esquemáticos y armaba la pcb. Luego de terminar de hacer esto, nos dimos cuenta que el segundo circuito no estaba respondiendo, pero no pudimos seguir trabajando ya que Misa y Aarón empezaron a presentar a la clase el nuevo estándar, el cual es el siguiente:

![Estándar hecho por les profesores, no me pertenece](./imagenes/estandar.png)

También nos dieron una lista de huellas estándar!! la pueden encontrar dentro de ``dis8644-2026-1-procesos-2/00-proyecto-02
/estandares.md`` o haciendo click en el siguiente link: <https://github.com/nicolasvaldesgreve/dis8644-2026-1-procesos-2/blob/main/00-proyecto-02/estandares.md>. De igual manera, aquí dejo un screenshot de la tabla:

![Huellas para todos!! aporte de Misa](./imagenes/huellas.png)
